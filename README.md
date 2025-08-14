# YTModerator
Comment censor tool (web extension) for youtube

A privacy-respecting browser extension that automatically detects and blurs toxic comments on YouTube, enhancing your browsing experience by shielding you from harmful or offensive content.

## Features

1. Real-Time DetectionAutomatically detects toxic comments as you browse YouTube.

2. Auto-Blur Toxic CommentsToxic content is blurred by default so that you aren’t exposed to harmful language unintentionally.

3. Unblur and Reblur ToggleUsers can unblur any blurred comment with a click, and also reblur it at any time using the added reblur button.

4. Multi-Language SupportThe extension first sends text to an external API for language detection and translation to English, ensuring toxic content is caught in any language.

5. AI-Based ClassificationUses a custom-trained deep learning model to assess toxicity based on multiple labels such as:

- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

6. Seamless IntegrationWorks in the background without interfering with your YouTube browsing flow.

## How It Works

The extension scans user-generated comments on YouTube.Each comment is sent to a language detection and translation service.The English version is analyzed using an AI model.If the comment is toxic, it is blurred.

You can toggle visibility using the Unblur or Reblur buttons.

## What Happens to Non-Toxic Comments?

If a comment is found to be non-toxic, the extension leaves it untouched.

## Who Should Use This?

1. People sensitive to online toxicity

2. Parents wanting safer content for their kids

3. Professionals who browse forums or social platforms at work

4. Anyone seeking a calmer, healthier web experience

## Privacy Statement

The extension does not store any data locally or remotely.

All processing is done on-the-fly to protect your privacy.

> Note : Third-party APIs are used only for language detection and translation, not for storing or tracking content.



Stay safe, stay focused. Let the web be a better place.
