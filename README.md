# WavLM
The SLM finetuning for Persian bsaed on the `microsoft/wavlm-base-plus` model.

## Dataset
Prepare a dataset of high-quality audio, with diverse number of speakers.

**production-level dataset**: 
- speakers: 100-500+
- gender: 50/50
- age: diverse
- hours: 200-500+ (each speaker 5-10 min audio)
- SNR ratio: > 15 dB
- sample rate: 16kHz
- duration: 1-15 seconds

> The key principle for SLM is that more speaker with less data is better than fewer speaker with lots of data.
