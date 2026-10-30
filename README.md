# Still Untitled: The Adam Savage Project Transcripts

This repository contains cleaned transcripts of every episode of [Tested](https://tested.com)'s [Still Untitled: The Adam Savage Project](https://www.youtube.com/playlist?list=PL4F7E816E0A6D9EDE) podcast.

## Motivation

This archive was created because Adam Savage's involvement in Industrial Light and Magic and MythBusters, along with his close personal connections over the years, gives him an insider perspective on many topics which has not been documented elsewhere.

## Process

### Transcription

1. Convert mp3 audio to 16kHz mono with FFmpeg.
2. Detect speech and speaker changes using pyannote Community-1. Divide speech regions into approximately 60-second sections, choosing quiet boundaries.
3. Perform local speech recognition using Qwen3-ASR 1.7B in BF16 through vLLM.
4. Add word timestamps using Qwen3-ForcedAligner 0.6B and assign speakers using acoustic speaker evidence.
5. Generate two additional readings using MOSS-Transcribe-Diarize in BF16 and Whisper large-v3 in FP16 through faster-whisper. *(Each model recovered wording or short replies that the others missed.)*
6. Join sections into timestamped, speaker-labelled turns, retaining all three transcriptons for comparison.

### LLM-guided Cleanup

7. Provide GPT 6 Pro with the transcriptions, episode metadata, and a specialist knowledge-base containing verified names, titles, news events, and accumulated podcast lore.
8. Read all three transcripts in full, using Qwen as the starting sequence and comparing alternative wording in context. Resolve disagreements from supporting evidence.
9. Check names, titles, equipment, and terminology against the knowledge-base. Research unresolved references. *(For example, “Gene Smart” → “Jean Smart.”)*
10. Resolve speaker identities using introductions, direct address, conversational context, and acoustic evidence. Retain “Unknown speaker” where identity remains uncertain.
11. Correct punctuation, capitalization, broken word boundaries, and transcription duplication while preserving genuine repetition.
12. Compare the completed draft against all three source transcriptions and revisit passages using nearby dialogue, recurring references across episodes, and additional research.
15. Update the shared knowledge-base with names, aliases, terminology, episode context, corrections, and sources.
16. Export final transcript with a standardized header.

## Guides

- [Cast](CAST.md): hosts and recurring guests, their backgrounds and episode appearances
- [Lore](LORE.md): major developments across the series
