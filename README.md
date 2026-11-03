# silent-ringtone-iphone

Just like it sounds: a silent ringtone for iPhone — 29 seconds of pure silence.

I created this repo because I like setting up my iPhone to "vibrate only" when
sound is turned on, and "truly silent" when in silent mode (so my phone never
rings or beeps in any way).

To do this, you need to turn on "Vibrate on ring" and have a silent ringtone.
However, a (free) silent ringtone is just about impossible to find.

## Download

| File | Format | Length | Best for |
| --- | --- | --- | --- |
| [Silence.mp3](https://github.com/dc0453/silent-ringtone-iphone/raw/master/Silence.mp3) | MP3 | 29s | iOS 26 and later — install directly on the iPhone, no computer needed |
| [Silence.m4r](https://github.com/dc0453/silent-ringtone-iphone/raw/master/Silence.m4r) | M4R (AAC) | 30s | Older iOS, or the Finder / iTunes transfer method |

iOS limits ringtones to roughly 30 seconds, so both files stay inside the limit.

## Setup A — iOS 26+, no computer required (recommended)

1. On your iPhone, open one of the download links above in Safari, or copy the
   link and download the file from the Files app.
2. In the **Files** app, find the downloaded file, long-press it, and choose
   **Share → Use as Ringtone**.
3. Confirm the name when iOS asks (for example "Silence").
4. Go to **Settings → Sounds & Haptics → Ringtone** and select **Silence**.

That's it — the ringtone is registered on the device without plugging anything in.

## Setup B — iOS 17 to 25, with a Mac (legacy)

As of iOS 17 there is no longer an iTunes technique, but the Finder can be used
to add ringtone files.

1. Plug your iPhone or iPad into your Mac and select "Trust" on the phone pop-up
   dialog (needed for enabling file transfers).
2. Open Finder and select your device in the left-hand bar.
3. Click "Manage Storage..." and open the "Tones" section.
4. Drag `Silence.m4r` into that list.
5. Set your ringtone to "Silence".

## After installing

Turn on **Vibrate on ring** and turn off **Vibrate on silent**, then make sure all
other notifications are set up to vibrate only.

The result: with the ringer on, the phone buzzes but stays quiet; in silent mode
it neither rings nor vibrates.

## License

Unlicense — see [LICENSE](LICENSE).
