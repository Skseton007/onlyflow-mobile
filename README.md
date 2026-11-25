# OnlyFlow

**Speak. It types. Anywhere.**

OnlyFlow is a free Android voice-typing app. Tap the floating OnlyFlow logo next to any text box, speak, and your words are typed for you, in any app. It runs on your own **free API key** (Gemini or Groq), so there is no subscription and no hidden cost.

<p align="center">
  <img width="140" alt="OnlyFlow screenshot 1" src="https://github.com/user-attachments/assets/b4b391c1-c9e9-48f5-b789-eb58516ba9b2" />
  <img width="140" alt="OnlyFlow screenshot 2" src="https://github.com/user-attachments/assets/9026e7c0-d42a-4acf-815b-b586c2dd8924" />
  <img width="140" alt="OnlyFlow screenshot 3" src="https://github.com/user-attachments/assets/0a7fc7f2-7959-408b-8d90-ed8ef26687b0" />
  <img width="140" alt="OnlyFlow screenshot 4" src="https://github.com/user-attachments/assets/c0503af9-bf15-46f5-bd76-f19e6c32fe39" />
  <img width="140" alt="OnlyFlow screenshot 5" src="https://github.com/user-attachments/assets/b60d1e80-dc06-4826-b100-59f5387d29f9" />
  <img width="140" alt="OnlyFlow screenshot 6" src="https://github.com/user-attachments/assets/25658f3e-ce26-42b7-a86b-27f61313fa77" />
</p>

## Download

Get the latest APK from the [Releases page](https://github.com/Skseton007/onlyflow-mobile/releases/latest). Open the APK on your phone and tap Install. If Android asks, allow "Install from unknown sources" for your browser or file manager.

After the first install, all future updates come inside the app as a popup. Your keys, settings and history stay safe after every update.

## What it does

- **Tap and talk:** tap the floating logo, speak, tap again. Your words are pasted into the text box. A hold-to-record style is also available in Settings.
- **Recording Mode:** hold the logo for 3 seconds to record classes, calls, YouTube videos or your own thoughts. You get the full transcript, a bullet-point summary and a question-and-answer section.
- **History:** everything you dictate or record is saved in the app.
- **Works offline:** if there is no internet, your recording is saved and processed automatically when you are back online. The audio is deleted once the text is created, so the app stays light.
- **Light on battery:** when you are not using it, it uses almost no battery, CPU or memory.
- **Your own free API key:** you can add several keys. If one fails, OnlyFlow automatically tries the next.

## First-time setup

When you open the app for the first time, a guide walks you through each step, one screen at a time:

1. **Overlay permission:** lets the floating logo appear over other apps.
2. **Accessibility permission:** lets OnlyFlow paste the text into the text box.
3. **Microphone permission:** so the app can hear you.
4. **Audio capture permission:** needed for Recording Mode.
5. **Battery setting:** set OnlyFlow to Unrestricted or No restrictions in your battery settings. This is important on Xiaomi, Oppo, Vivo and Samsung phones, which otherwise stop the app in the background.
6. **Add a free API key:** see below.

You can change all of these later in Settings.

## Get a free API key

OnlyFlow needs an AI key to turn your speech into text. These two are free and take about two minutes.

### Option 1: Groq (free, very fast)

1. Go to [console.groq.com](https://console.groq.com) and sign in with your Google account or email.
2. Click **API Keys** in the top bar.
3. Click **Create API Key** and give it any name.
4. Copy the key right away. Groq shows it only once.
5. In OnlyFlow, open **Settings, AI keys**, choose Groq and paste the key.

This is Groq (G-R-O-Q), not Grok from X.

### Option 2: Google Gemini (free)

1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey) and sign in with your Google account.
2. Click **Create API key**.
3. Pick a project, or create a new one.
4. Copy the key.
5. In OnlyFlow, open **Settings, AI keys**, choose Gemini and paste the key.

Both give you a free tier with usage limits, which is plenty for daily dictation. Adding both keys is a good idea, so OnlyFlow can switch if one hits its limit.

OpenRouter and OpenAI keys also work, but OpenAI is usually paid.

## How to use

1. Tap any text box in any app. The OnlyFlow logo appears next to it.
2. Tap the logo and speak.
3. Tap the logo again. Your words are pasted.
4. For long audio, hold the logo for 3 seconds to start Recording Mode.

## Updates

This repository holds the config file that the app reads for texts, links and the update notice. It is managed by the OnlyFlow Control Panel, so please do not edit `config.json` by hand.

## Created by

Created by **Seton Jr**. Telegram: [@Affordablesellers](https://t.me/Affordablesellers)

## License

Released under the [MIT License](LICENSE). You are free to use, share and modify it, as long as you keep the credit and the license notice.
