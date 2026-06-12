# talavarp — feedback

This is the public feedback channel for **talavarp**, a Chrome extension that
overlays translated subtitles on [RÚV](https://www.ruv.is) programmes. Many
programmes on ruv.is carry Icelandic subtitles but no translation; talavarp
fetches the Icelandic subtitles, translates them into any of 17 languages,
and renders them over the video — synced, styleable, and optional.

**[Install talavarp from the Chrome Web Store](https://chromewebstore.google.com/detail/talavarp/nppomflhadnkechkpfgemnkiebdoaapp)**

Found a bug? Missing a feature? Have a question? You're in the right place:
**[open an issue](../../issues/new)**. Issues in English or Icelandic are
both welcome — skrifaðu endilega á íslensku ef þú vilt.

## Reporting a bug

The more of this you can include, the faster it gets fixed:

- **What happened**, and what you expected to happen instead.
- **The programme URL** (`ruv.is/sjonvarp/spila/…`) where it went wrong.
- **Your target language**, and whether you were using the free built-in
  translation or your own Gemini API key.
- **Extension version** (shown at `chrome://extensions`) and **browser
  version**.
- A **screenshot** if the problem is visual (subtitle position, styling,
  overlap, etc.).

⚠️ **Never paste your Gemini API key into an issue.** Issues here are public.
If a screenshot shows the extension's settings, check that the key field
isn't visible.

## Requesting a feature

Open an issue describing what you'd like and why. It helps to know the
situation it would improve — e.g. which programmes, which language, what
you're doing when you miss it.

## A few notes

- talavarp is an independent project and is **not affiliated with RÚV**.
  Problems with the RÚV player or site itself are best reported to RÚV.
- talavarp collects no personal data and contains no analytics. The only
  data that leaves your browser is the programme's subtitle text (which RÚV
  publishes publicly), sent to the translation service you've chosen. See
  the full [privacy policy](privacy-policy.md).
- The free built-in translation is rough but serviceable; a Gemini API key
  gives noticeably better quality. Translation-quality reports are still
  welcome — please say which mode you were using.

## Supported languages

English, Polish, Spanish, Romanian, Lithuanian, Ukrainian, Russian,
Filipino, Arabic (right-to-left supported), Croatian, Serbian, Bosnian,
Portuguese, Vietnamese, German, Czech, Greek.
