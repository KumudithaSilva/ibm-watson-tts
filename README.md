# 🔊 IBM Watson Text to Speech with Google Colab

This project demonstrates how to use **IBM Watson Text to Speech API** to convert text into spoken audio using a Google Colab notebook. The result is saved as an MP3 file directly to your Google Drive.

---

## 📁 Project Overview

- 🔐 Securely read IBM Watson credentials from a CSV file in Google Drive.
- 📄 Read a text file containing the input message.
- 🔊 Convert the text to audio using IBM's Text to Speech service.
- 💾 Save the audio output as an MP3 file to Google Drive.

---

## ✅ Requirements

- Google Account (for Google Colab + Drive)
- IBM Cloud Account with Text to Speech enabled
- Your `apikey` and `url` for the TTS service
- CSV file with credentials in the following format:

```csv
Key,Value
apikey,your-ibm-api-key
url,https://api.your-region.text-to-speech.watson.cloud.ibm.com
```

---

## 🎙️ Voice List


| 🌍 Language             | 🗨️ Voice Name   | 🎤 Voice ID            |
| ----------------------- | ---------------- | ---------------------- |
| 🇺🇸 English (US)       | Michael (male)   | `en-US_MichaelV3Voice` |
| 🇺🇸 English (US)       | Allison (female) | `en-US_AllisonV3Voice` |
| 🇯🇵 Japanese           | Emi (female)     | `ja-JP_EmiV3Voice`     |
| 🇪🇸 Spanish (Spain)    | Enrique (male)   | `es-ES_EnriqueV3Voice` |
| 🇫🇷 French (France)    | Renée (female)   | `fr-FR_ReneeV3Voice`   |
| 🇩🇪 German             | Birgit (female)  | `de-DE_BirgitV3Voice`  |
| 🇮🇳 Hindi              | Ananya (female)  | `hi-IN_AnanyaV3Voice`  |
| 🇨🇳 Chinese (Mandarin) | Wang (male)      | `zh-CN_WangWeiVoice`   |




