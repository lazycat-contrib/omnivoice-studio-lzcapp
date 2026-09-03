# VoiceStudio for LazyCat

This repository packages [VoiceStudio](https://github.com/debpalash/VoiceStudio) for LazyCat Cloud.

VoiceStudio is an open-source, fully local ElevenLabs alternative for voice cloning, voice design, video dubbing, dictation, transcription, and audiobook creation in 646 languages.

## Deployment

The setup wizard requires an `OMNIVOICE_API_KEY`. Use a long random value. On first launch, VoiceStudio may download several gigabytes of models.

Runtime data is stored under `/lzcapp/var`; reconstructable Hugging Face cache data is stored under `/lzcapp/cache`.

## Upstream

- Image: `palashdeb/omnivoice-studio`
- Version: `0.5.1`
- License: AGPL-3.0
