# youtube-sampler
Randomly sampling YouTube videos

# Requirements
- Python 3.12 (`brew install python` or the Windows way via MS Store)
- FFMPEG (`brew install ffmpeg` or the Windows way via ffmpeg website)

# Installation
`pip3 install -r requirements.txt -t ./python_modules`

# Usage
- Open words.txt, enter one word per line of what you want to search for samples.
- Run `python3 app/random-sampler.py` from folder's root project, the outputs are into the `wav/` folder.
- Stop generating samples by pressing Ctrl+C (or ^C on macOS).

# Idea and code credits
Credits to [@ColugoMusic](https://twitter.com/ColugoMusic) and [@hazedbeats](https://twitter.com/hazedbeats).

Original tweet with code here : https://twitter.com/ColugoMusic/status/1726001266180956440
