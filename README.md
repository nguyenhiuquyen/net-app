# 🎬 Netflix UI Clone (Expo + React Native)

A **high-fidelity, production-grade mobile UI clone** of Netflix built using [React Native](https://reactnative.dev/) and [Expo](https://expo.dev). This project showcases advanced animation techniques, gesture interactions, and smooth transitions — delivering a near-native, immersive experience inspired by the official Netflix app.

<p align="center">
  <img src="assets/gifs/demo.gif" alt="Demo" width="300" />
</p>

---

## 🔥 Highlights

- 🎞 **Pixel-perfect design** closely replicating Netflix UI  
- 🌀 **Smooth animations** using Reanimated 2 and shared transitions  
- 🤌 **Gesture-enabled navigation** and modal interactions  
- 🎮 **Interactive profile switching**, haptics, and custom sounds  
- 📱 Built with **Expo SDK**, optimized for cross-platform deployment

---

## ✨ Features

### 👤 Profile Management
- Animated profile selection with **staggered load-in**
- Seamless profile switch with **sound effects** and **haptic feedback**
- Modular & scalable for multiple user contexts

### 🧭 Navigation & UX
- Custom bottom tabs with **sliding transitions**
- Gesture-enabled **modals and overlays**
- **Shared element transitions** for media previews
- iOS-style **presentation modals**
- Tilt effects for immersive featured content

### 🧩 Content & Discovery
- Home screen with **carousel & vertical sections**
- "New & Hot" section with dynamic cards
- Full-screen **teaser video player**
- **Game showcase**, search, and download manager
- Expandable **categories**, dynamic font loading

### ⚙️ Performance
- **Worklet-based** animations via Reanimated 2
- Native gesture handling via Gesture Handler
- Optimized list rendering (FlatList & virtualized views)
- Low memory footprint, high frame-rate UX

---

## 🧰 Tech Stack

| Tool/Library                 | Description                               |
|-----------------------------|-------------------------------------------|
| [Expo](https://expo.dev)    | Fast development & deployment environment |
| React Native                | Core mobile UI framework                  |
| [Expo Router](https://expo.dev/router) | File-based navigation system             |
| [Reanimated 2](https://docs.swmansion.com/react-native-reanimated/) | Declarative, performant animations        |
| [Gesture Handler](https://docs.swmansion.com/react-native-gesture-handler/) | Native gesture support                    |
| [Expo AV](https://docs.expo.dev/versions/latest/sdk/av/) | Audio & video playback                   |
| [Expo Haptics](https://docs.expo.dev/versions/latest/sdk/haptics/) | Haptic feedback                          |

---

## 🗂️ Project Structure

\`\`\`
project-root/
├── app/
│   ├── (tabs)/
│   │   ├── (profile)/           # Profile selection
│   │   ├── index.tsx            # Home screen
│   │   └── new.tsx              # New & Hot
│   ├── movie/                   # Movie details
│   ├── _layout.tsx             # Global layout wrapper
│   └── search.tsx              # Search UI
├── components/
│   ├── MovieList/              # Media lists
│   ├── GameList/               # Game cards
│   ├── FeaturedContent/        # Featured UI
│   ├── BottomSheet/            # Sheets & modals
│   ├── navigation/             # Tab & stack navigation
│   └── WhoIsWatching/          # Profile entry
├── hooks/                      # Custom hooks
│   ├── useCachedResources.ts
│   ├── useColorScheme.ts
│   ├── useDeviceMotion.ts
│   └── useOverlayView.ts
├── data/                       # Static mock data
│   ├── movies.json
│   ├── new.json
│   └── users.json
└── contexts/                   # Global state contexts
\`\`\`

---

## 📌 Roadmap / TODOs

- [ ] **Shared transitions** in modal navigation  
- [ ] Fix: Disable "shift animation" on back *(see branch \`router-4\` w/ React Navigation 7)*  
- [ ] Add **X-Ray style content details**  
- [ ] Implement **full-screen video player**  
- [ ] **Dynamic theming** via color extraction from thumbnails

---

## 🤝 Contributing

We welcome community contributions! To contribute:

1. **Fork** this repository  
2. Create a new branch: \`feature/your-feature-name\`  
3. Submit a detailed **Pull Request**

Please ensure your code follows project conventions and includes meaningful documentation when needed.

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).  
You are free to use, modify, and distribute this project for personal and commercial purposes.

---

> Inspired by Netflix. This is a UI/UX clone and **not affiliated** with Netflix, Inc.
