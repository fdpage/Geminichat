# Gemini Messenger

Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)

Base64 encoded appstate from [c3c-fbstate](https://github.com/c3cbot/c3c-fbstate)
### libmagic issue

If you encounter an error like this:

`ImportError: failed to find libmagic.  Check your installation`

You need to install libmagic.

For Termux:

```bash
pkg install sox
```
For Other Platforms, try installing `python-magic-bin`:

```bash
pip install python-magic-bin==0.4.14
```
