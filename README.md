# MediaPrism

A portable image, audio and video converter and compressor for Windows 10/11 (64-bit). No install and no runtimes: unzip it anywhere, including a flash drive, and run `MediaPrism.exe`.

- Converts between about 100 image formats and hundreds of audio/video formats, including many game and retro formats (Westwood VQA/WSA/AUD, Smacker, Bink, vgmstream audio, and more).
- **GIF Studio**: edit GIFs, APNGs and WebPs (resize, crop, rotate, reverse/boomerang, speed, cut, frame-by-frame), add effects, text, censor boxes and images, remove backgrounds, optimise them (lossy, colours, transparency, duplicate frames), fit them under a size limit (Discord, Slack, X...), split them into frames or a sprite sheet, make GIFs from videos, pictures (with crossfades), screen recordings or links (Discord, Tenor, Giphy, YouTube...), open Aseprite sprites and animated cursors, and save with gifski/gifsicle optimisation (or as an animated cursor).
- **Generate**: make AI pictures entirely on your own PC: create from a description with 45 art styles, restyle a picture, edit it by instruction ("make her hold a yellow umbrella") with "Match Style" keeping the picture's own look, inpaint a painted area, and upscale 2x to 16x; up to 100 pictures per click. Models (FLUX.2 [klein], FLUX.1-schnell, SDXL, SD 1.5 or your own) are downloaded in the app; a hardware score shows what your PC can handle.
- **Personal models** (optional Training add-on, installed from the Generate tab; needs an NVIDIA graphics card): copy FLUX.2 [klein] 4B, SD 1.5 or SDXL under your own name, rate its pictures and fix the bad ones, add photos of things it has never seen, and train it on your own PC in the Training Studio.
- Plays and converts MIDI (plus game music in XMI and MUS) through a SoundFont, and can transcribe recordings into MIDI (experimental).
- Compress, convert, or both, with optional ZIP/7z archives.
- Video codec choice: H.264 (plays everywhere), H.265 or AV1 (the smallest files).
- GPU acceleration (NVIDIA, AMD, Intel), a usage limiter, presets, trim/crop/resize, and a watch folder.
- Updates itself quietly in the background (can be turned off).

## Download
Get **MediaPrism-x.y.z-portable.zip** from the [latest release](../../releases/latest), unzip it, and run `MediaPrism.exe`.

## Responsible use
Only convert files you own or have permission to use. Game videos, music and artwork are copyrighted by their publishers. The Westwood and Smacker encoders were written for interoperability and are not affiliated with or endorsed by Westwood Studios, Electronic Arts or RAD Game Tools. AI pictures: don't make pictures of real people without their consent or anything meant to deceive or harass, and respect each model's licence; sexual content involving minors is always refused and adult content is filtered by default. Personal models: only train them on pictures and photos you're allowed to use, never on photos of real people without their consent, and don't use them to imitate someone. MediaPrism comes with no warranty.

## Included software
FFmpeg 7.1.1 (GPL; build by gyan.dev, source: https://ffmpeg.org/releases/ffmpeg-7.1.1.tar.xz), ImageMagick, 7-Zip, vgmstream, RAD Video Tools, TinySoundFont, the GeneralUser GS SoundFont, Spotify's Basic Pitch, Microsoft ONNX Runtime, gifsicle, gifski, yt-dlp, stable-diffusion.cpp, llama.cpp and ggml (MIT). Their licences are in `assets\licenses`, and the README inside the download has details. AI models are not included: the app downloads them on request, under their own licences.

Created by Smiling_Winner · [X](https://x.com/smiling_winner) · [YouTube](https://www.youtube.com/@SmilingWinner606)
