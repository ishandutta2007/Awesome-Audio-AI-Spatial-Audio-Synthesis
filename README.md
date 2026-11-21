# Awesome-Audio-AI-Spatial-Audio-Synthesis

# Top Audio AI & Spatial Audio Synthesis Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on AI Audio Synthesis, Spatial Audio Rendering, Speech Enhancement, Neural Sound Generation & Audio Workstations*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Audio AI & Spatial Audio Synthesis**. These tools generate, synthesize, spatialize, denoise, master, and edit speech, soundscapes, music, and 3D binaural audio using neural audio codecs, diffusion/flow-matching synthesizers, Ambisonics/HRTF acoustic engines, and modular digital audio workstations.

**Examples** include Descript, Dolby.io, Auphonic, Krisp, Cleanvoice AI, Adobe Podcast, LANDR, AudioNodes, Soundop, WavePad, and LUC4N3X/Levyra-deepsound (the category leaders and notable community entries). 

**Open-source emphasis**: This section is heavily expanded with every major active project for neural audio/music/SFX synthesis (`Stable Audio Open`, `AudioCraft / MusicGen & AudioGen`, `Riffusion`), physics-based spatial audio & Ambisonics (`Steam Audio`, `IEM Plug-in Suite`, `Resonance Audio`), speech enhancement (`DeepFilterNet`, `Resemble Enhance`), and open-source audio players/DAWs — ideal for audio engineers, game/XR sound designers, podcasters, ML researchers, and open-source builders.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Descript (Studio Sound & Overdub)](https://descript.com)**  
  AI-powered audio and video production suite combining text-based transcript editing, neural voice synthesis, and one-click Studio Sound voice isolation.

- **[Dolby.io](https://dolby.io)**  
  Cloud media and communications API platform providing spatial audio synthesis, AI speech enhancement, dynamic leveling, and multi-channel mastering.

- **[Auphonic](https://auphonic.com)**  
  Automated AI audio post-production service and API delivering adaptive leveling, noise/reverb reduction, and broadcast loudness normalization (LUFS).

- **[Krisp](https://krisp.ai)**  
  Real-time AI noise cancellation, voice isolation, and acoustic echo cancellation desktop app and on-device SDK for VoIP, streaming, and voice agents.

- **[Cleanvoice AI](https://cleanvoice.ai)**  
  Cloud-based AI podcast post-production tool engineered to detect and remove filler words, mouth sounds, breath noises, and dead air across multiple languages.

- **[Adobe Podcast (Enhance Speech)](https://adobe.com)**  
  Browser-based AI voice restoration and audio synthesis tool transforming noisy, echo-heavy recordings into studio-quality vocal tracks.

- **[LANDR](https://landr.com)**  
  Cloud-based AI audio mastering, stem separation, and music production platform offering automated EQ, compression, and stereo enhancement.

- **[AudioNodes](https://audionodes.com)**  
  Browser-based and desktop modular synthesizer and digital audio workstation (DAW) featuring visual node-based sound synthesis, multi-track sequencing, and real-time DSP effects.

- **[Soundop](https://soundop.com)**  
  Windows audio editor and multitrack workstation combining spectral editing, batch processing, VST/VST3 plugin hosting, and precision mastering tools.

- **[WavePad (NCH Software)](https://nch.com.au)**  
  Cross-platform audio and music editing software offering spectral analysis, noise reduction, batch processing, and DirectX/VST effect chains.


## Open-Source GitHub Projects

- **[AudioCraft (Meta MusicGen & AudioGen)](https://github.com)**  
  Flagship open-source PyTorch library for deep learning audio synthesis, featuring `MusicGen` for text-to-music generation, `AudioGen` for environmental SFX synthesis, and `EnCodec` neural audio compression.

- **[Stable Audio Open (`stable-audio-tools`)](https://github.com)**  
  Open-source generative audio framework from Stability AI for training and running diffusion-transformer models that synthesize 44.1 kHz stereo sound effects, foley, and ambient audio from text prompts.

- **[Steam Audio (`ValveSoftware/steam-audio`)](https://github.com)**  
  Open-source physics-based spatial audio synthesis SDK providing HRTF binaural rendering, acoustic occlusion, geometry-based raytraced reflections, and Ambisonics for games and XR.

- **[IEM Plug-in Suite](https://github.com)**  
  Comprehensive open-source suite of spatial audio and Higher-Order Ambisonics (HOA) VST/LV2 plugins for 3D sound field synthesis, binaural decoding, and room simulation.

- **[Resonance Audio (Google)](https://github.com)**  
  Cross-platform open-source spatial audio SDK synthesizing realistic 3D sound propagation and room acoustics at scale for mobile, desktop, and VR applications.

- **[DeepFilterNet](https://github.com)**  
  Low-complexity, real-time open-source deep learning framework for full-band (48 kHz) speech enhancement and background noise suppression with Rust/Python and PipeWire/LADSPA support.

- **[Resemble Enhance](https://github.com)**  
  Open-source AI speech denoising and audio super-resolution toolkit that removes background noise and synthesizes crisp high-frequency vocal harmonics up to 44.1 kHz.

- **[Demucs (Meta Research)](https://github.com)**  
  State-of-the-art open-source hybrid Transformer/waveform source separation engine for isolating vocals, drums, bass, and instrumental stems from mixed audio.

- **[Audacity](https://github.com)**  
  Cross-platform open-source multi-track audio editor and recorder supporting OpenVINO AI noise suppression, music generation/separation plugins, spectral editing, and VST3 effects.

- **[LUC4N3X/Levyra-deepsound](https://github.com/LUC4N3X/Levyra-deepsound)**  
  Open-source GPLv3 cross-platform audio player for Android and Windows featuring 10-band EQ, AutoEQ headphone profiles, pitch/speed DSP controls, ReplayGain, and local/streamed library unification with zero telemetry.

- **[matchering](https://github.com)**  
  Open-source Python library and web application for automated reference-based audio mastering, matching RMS, frequency response, peak amplitude, and stereo width.

### Additional Strong Open-Source Options

- **[Riffusion / Riffusion Hobby](https://github.com)** for real-time diffusion-based audio and music synthesis via spectrogram generation.
- **[SOFA / libmysofa](https://github.com)** for open-source Head-Related Transfer Function (HRTF) dataset loading and personalized binaural spatial audio rendering.
- **[Pedalboard (Spotify)](https://github.com)** for high-performance Python audio processing supporting VST3/Audio Unit plugins, studio effects, and streaming I/O.
- **[RNNoise](https://github.com)** for lightweight C-based recurrent neural network noise suppression integrated across WebRTC, OBS Studio, and VoIP pipelines.
- **[SuperCollider](https://github.com)** and **[Pure Data (Pd)](https://github.com)** for open-source real-time algorithmic audio synthesis, spatial multichannel routing, and procedural sound design.

**Frameworks for building custom systems**: Combine **Stable Audio Open** or **AudioCraft** for generative sound/music synthesis, **Steam Audio** or **IEM Plug-in Suite** for 3D spatial rendering, and **DeepFilterNet + Pedalboard** for automated AI speech cleanup and mastering.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Generative audio synthesis models (such as `Stable Audio Open` and `AudioCraft`) carry specific model weight licenses and training data terms; review licensing requirements before commercial distribution.
- Real-time spatial audio rendering and neural speech enhancement pipelines require careful buffer sizing and sample-rate alignment (44.1 kHz / 48 kHz) to prevent audio dropouts.

---

**Made for audio engineers, spatial sound designers, podcasters, game developers, and open-source AI researchers.**  
Let's make AI audio synthesis and spatial sound engineering more open, creative, and accessible.
