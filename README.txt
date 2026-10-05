চালানোর নিয়ম (ইন্টারনেট লাগবে, three.js লোড হওয়ার জন্য):
1. এই ফোল্ডারে টার্মিনাল/CMD খুলুন
2. চালান:  python -m http.server 8000
3. ব্রাউজারে খুলুন:  http://localhost:8000
(সরাসরি index.html ডাবল-ক্লিক করলে চলবে না, কারণ ব্রাউজার .glb ফাইল লোড করতে দেয় না)

Multiplayer (Firebase) নিয়ম:
- নাম লিখে 🌍 ঢুকো বাটন চাপো, একই লিংক থেকে বন্ধুরা ঢুকলে live দেখা যাবে
- Firebase Console > Realtime Database > Rules-এ দাও:
  {"rules": {".read": true, ".write": true}}
  (শুধু টেস্টের জন্য; পরে tight rules বসিও)
