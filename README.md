🚀 SpeakGenie – Flutter Assignment

SpeakGenie is a mobile app UI developed using Flutter based on the assignment requirements provided.
This project implements the main core UI screens, microphone flow & responsive design.

📱 Features Implemented

✔ Home Screen (pixel-perfect based on Figma)
✔ AI Practice section (Doraemon & Spiderman cards)
✔ Human practice card
✔ Audio stories
✔ App-wide UI theme
✔ Recording → Stop → Playback flow (Mocked / Functional)
✔ Avatar + assets
✔ Assets based UI

✨ Screens Built
Screen	Status
Home Screen	✔ done
Chatbot Screen	✔ done / placeholder
Profile	✔ done
Leaderboard	✔ done
Membership	✔ done
🛠 Tech Used

Flutter (Stable channel)

Dart

Provider / SetState

flutter_sound

permission_handler

📂 Folder Structure
lib/
 ├── ui
 │    ├── screens
 │    ├── widgets
 │
 ├── services
 ├── utils
 ├── main.dart
assets/
pubspec.yaml

🎧 Audio Support

Implemented basic audio recorder flow:

request mic permission

record voice

stop recording

playback recorded audio
