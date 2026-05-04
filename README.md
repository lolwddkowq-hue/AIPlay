# AIPlay

AIPlay is a safe AI gameplay-analysis tool for reviewing BGMI screenshots or recorded gameplay from PC/MuMu Player.

## What it does

- Analyzes screenshots or video frames.
- Gives coaching tips about positioning, cover, rotation, map awareness, and decision-making.
- Uses Node.js and Hugging Face-hosted vision-language models such as Qwen-VL.

## What it does not do

- No auto-aim.
- No auto-fire.
- No recoil macros.
- No emulator control.
- No anti-cheat bypass.
- No live-match automation.

## Setup

```bash
npm install
cp .env.example .env
node src/analyze-frame.js samples/frame.png
