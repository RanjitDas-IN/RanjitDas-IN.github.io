## This repo is for testing purposes only

## TTS Accelerator

> *Real-time natural speech generation in seconds, even for extremely long sentences up to 16k words.*

> This library can turn **text into speech** almost instantly. Even if you give it a super long paragraph — up to 16,000+ words — it doesn’t takes too much time. It starts speaking in just 2 seconds, making it feel like real-time talking without losing the voice quality.

[![PyPI version](https://badge.fury.io/py/tts-accelerator.svg)](https://pypi.org/project/tts-accelerator/)&emsp;&emsp;
[![Download](https://pepy.tech/badge/tts-accelerator)](https://pepy.tech/project/tts-accelerator)



Want to ask questions or share ideas?  
👉&emsp;[![](https://dcbadge.vercel.app/api/server/JVzAfRjyxV?style=flat&compact=True)](https://discord.gg/JVzAfRjyxV)
&emsp;— we're active and friendly!


💡 **Actively Developed & Maintained**: This project is continuously improved with regular updates, bug fixes, and support. You're never alone — the journey keeps moving forward! 🚀🔧
[![GitHub Repo](https://img.shields.io/badge/GitHub__Repo-black?logo=github&style=flat)](https://github.com/RanjitDas-IN/tts-accelerator)&emsp;&emsp;
[![GitHub Repo](https://img.shields.io/badge/GitHub__Repo-black?logo=github&style=social)](https://github.com/RanjitDas-IN/tts-accelerator)

Feel free to reach out, open issues, or suggest ideas — we’re building this together. 🤝

My email: ranjitdax89@gmail.com
---
## 📖 Quick Index

- [💡 Insight](#insight)
- [✨ Key Features](#key-features)
- [⬇️ Installation](#installation)
- [📚 Examples](#examples)
- [📚 Requirements](#requirements)


## 💡Insight


TTS Accelerator is a smart and powerful tool that turns text into speech super fast. You can give it a really long paragraph — even up to 16,000 characters — and it starts speaking in just **2 seconds**.

Most other TTS systems wait until the full audio is ready before they start, which can take ages. *But this one is different* — it starts playing while it’s still generating. So, you can hear the voice as soon as the script runs — no matter how long the text is. The result? Natural, smooth speech with no delay.


## ✨Key Features


- **Super Fast Speech (Real-Time TTS)**: Begins speaking in just 2–3 seconds, even for extremely long texts — up to 16,000+ words.
- **Highly Compatible**: Seamlessly works with popular TTS engines like Edge-TTS (tested), Coqui TTS, and even API-based services like ElevenLabs, Typecast.ai, and more.
- **Streaming Playback**: Audio starts playing instantly while it’s still being generated — no delay, no wait.
- **Engine-Agnostic Core**: Designed to plug into any TTS backend of your choice without needing major changes.
- **Minimal API**: Just a single function call to start speaking — `speak_text(text)`.
- **Zero-Delay Playback**: Audio plays with zero delay, It is a smart system that uses fast RAM-based buffering and a separate producer-consumer pipeline to keep things smooth and super quick.


## 🔧Installation

You can install it from [PyPI](https://pypi.org/project/tts-accelerator/) by running the following command:

```
pip install tts-accelerator
```

Or you can install it from [source](https://github.com/RanjitDas-IN/tts-accelerator): 

```
pip install .
```

GitHub&emsp;[![GitHub Repo](https://img.shields.io/badge/GitHub__Repo-black?logo=github&style=social)](https://github.com/RanjitDas-IN/tts-accelerator)


## 📚Examples

Simple Usage:

```python
import tts_accelerator as tts

text = ("""Hello, 'TTS-Accelerator' achieves near-instant speech generation. Converting extremely long texts (up to 16 thousand + characters) into natural voices, high-quality audio within just 2–3 seconds, delivering breakthrough real-time performance without sacrificing voice clarity. Thank you!!""")

tts.speak_text(text)
# it will generate the audio in less then 3 seconds regardless of number of lines in the 'text variable'
```

## 📦Requirements

- Python _v3.8+_
