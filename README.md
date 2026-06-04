# Nerd Tracker 🐱

## 📱 About

**Nerd Tracker** is a cross-platform mobile app (iOS & Android) for gamers who want to
keep track of their video game collection. Search any title from the IGDB catalogue,
add it to your library with a status (Playing, Played, Wishlist, Dropped), rate it,
and write reviews to share with the community.

### ✨ Features

- 🎮 **Game Collection** — track every game with status, personal rating (0–10) and notes
- 🔍 **Smart Search** — powered by IGDB, with filters by genre, decade and category (Game / DLC / Expansion)
- 💡 **Personalised Recommendations** — genre affinity engine that suggests games based on your collection
- ✍️ **Community Reviews** — write reviews with spoiler protection (AI-assisted detection), like and comment on
others'
- 👤 **Social Profiles** — follow users, send friend requests, explore public collections
- 🤖 **KittenBot** — in-app AI assistant (Llama 3.1) for game recommendations and chat
- 🌍 **Multilingual** — fully localised in English, Italian, Spanish, German and French
- 🌙 **Dark / Light theme** — system-aware with manual override

---
Tech Stack

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | [Expo](https://expo.dev/) ~54 (New Architecture + React Compiler) |
| **UI** | React Native 0.81 + [NativeWind](https://www.nativewind.dev/) v4 (Tailwind CSS) |
| **Routing** | Expo Router v6 (file-based, typed routes) |
| **Language** | TypeScript 5.9 (strict) |
| **State** | React Context + AsyncStorage (optimistic local-first updates) |
| **Backend** | [Supabase](https://supabase.com/) — Postgres, Auth, RPC, RLS, Realtime |
| **Game Data** | [IGDB API](https://www.igdb.com/api) via Twitch OAuth2 |
| **AI Features** | Spoiler detection + KittenBot chat (Llama 3.1) |
| **Crypto** | `@noble/ciphers` + `@noble/hashes` for client-side encryption |
| **Notifications** | Expo Notifications (push) |
| **CI / Deploy** | EAS Build + EAS Update (OTA updates) |
