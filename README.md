# VideoEditor

A modern, open-source web-based video editor built with [Next.js](https://nextjs.org/) and [Remotion](https://www.remotion.dev/). Create, edit, and render stunning videos directly in your browser with a beautiful, intuitive interface.

---

## ✨ Features

- **Drag-and-drop Timeline**: Arrange, trim, and reorder video and image clips with a smooth, interactive timeline.
- **Multiple Aspect Ratios**: Instantly switch between landscape, portrait, square, and classic video formats.
- **Transitions**: Add fade, slide, and other transitions between clips for professional results.
- **Live Preview**: See your edits in real-time with a high-fidelity video player powered by Remotion.
- **Media Upload**: Import images and videos from your device and add them to your project.
- **Customizable Animations**: Leverage Remotion and Framer Motion for advanced, customizable video effects.
- **Export/Render**: Render your final video using Remotion’s powerful rendering engine (local rendering demo included).
- **Responsive UI**: Works great on desktop and mobile devices.

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/videoeditor.git
cd videoeditor
npm install
# or
yarn install
```

### Development

Start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to use the editor.

### Rendering Videos

To preview or render videos using Remotion:

```bash
npm run preview   # Live Remotion preview
npm run render    # Render video to out/video.mp4
```

---

## 🛠️ Project Structure

- `src/app/video-editor/` — Main video editor UI and logic
- `src/components/Timeline.js` — Interactive timeline component
- `src/remotion/` — Remotion video compositions and rendering logic

---

## 🤝 Contributing

Contributions are welcome! Please open issues or pull requests for new features, bug fixes, or suggestions.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## 📄 License

This project is open source and available under the [MIT License](./LICENSE).
