# Beat Boxx 🎵

A fun and interactive music/beatbox application built with Angular. Create beats by tapping on colorful pads that play different sounds and create visual bubble effects!

## 🎯 Features

- **6 Interactive Sound Pads**: Each pad plays a unique sound effect
- **Visual Effects**: Beautiful animated bubbles appear when you tap a pad
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Audio**: Instant sound feedback on interaction
- **Colorful UI**: Vibrant color scheme with smooth animations

## 🎨 Demo

[Live Demo](https://thequarky.github.io/beat-boxx/) (GitHub Pages)

## 🛠️ Technologies Used

- **Angular 9.1.1**: Front-end framework
- **TypeScript**: Programming language
- **Express.js**: Node.js server for local testing
- **HTML5 Audio API**: For sound playback
- **CSS3 Animations**: For visual effects

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v12.x or higher)
- **npm** (v6.x or higher)
- **Angular CLI** (v9.x)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/theQuarky/beat-boxx.git
cd beat-boxx
```

2. Install dependencies:
```bash
npm install
```

## 💻 Development Server

### Using Angular CLI (Recommended for Development)

Run the Angular development server:
```bash
ng serve
```

Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Using Express Server (For Testing Production Build Locally)

1. Build the application:
```bash
npm run build
```

2. Start the Express server:
```bash
npm start
```

The server will start on `http://localhost:8080/`.

## 🏗️ Build

Run the build command to compile the project:
```bash
npm run build
```

The build artifacts will be stored in the `dist/BeatBoxx` directory.

For production build:
```bash
npm run build -- --prod
```

## 🚢 Deployment

### Deploy to GitHub Pages

This project is configured for easy deployment to GitHub Pages.

1. **First-time setup**: Install the Angular GitHub Pages deployment tool:
```bash
npm install -g angular-cli-ghpages
```

2. **Build for production**:
```bash
npm run build -- --prod --base-href "https://theQuarky.github.io/beat-boxx/"
```

3. **Deploy to GitHub Pages**:
```bash
npx angular-cli-ghpages --dir=dist/BeatBoxx
```

Or use the automated GitHub Actions workflow (see `.github/workflows/deploy.yml`).

### Deploy to Heroku

The project includes Heroku configuration:

1. Create a Heroku app:
```bash
heroku create your-app-name
```

2. Push to Heroku:
```bash
git push heroku main
```

The `heroku-postbuild` script in `package.json` will automatically build the app.

## 📁 Project Structure

```
beat-boxx/
├── src/
│   ├── app/
│   │   ├── header/           # Header component
│   │   ├── pads/             # Sound pads component
│   │   ├── visual/           # Visual effects component
│   │   ├── app.component.*   # Root component
│   │   └── app.module.ts     # App module
│   ├── assets/
│   │   └── sounds/           # Audio files (mp3)
│   ├── environments/         # Environment configurations
│   └── index.html           # Main HTML file
├── server.js                # Express server for production
├── angular.json             # Angular configuration
├── package.json             # NPM dependencies
└── README.md               # This file
```

## 🎮 How to Use

1. Open the application in your browser
2. Click or tap on any of the 6 colorful pads
3. Each pad plays a different sound and creates a bubble animation
4. Mix and match sounds to create your own beats!

## 🧪 Running Tests

### Unit Tests

Run unit tests via [Karma](https://karma-runner.github.io):
```bash
npm test
```

### End-to-End Tests

Run end-to-end tests via [Protractor](http://www.protractortest.org/):
```bash
npm run e2e
```

## 🔍 Linting

Run TSLint to check code quality:
```bash
npm run lint
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**theQuarky**

- GitHub: [@theQuarky](https://github.com/theQuarky)

## 🙏 Acknowledgments

- Sound effects from various sources
- Inspired by drum pad machines and beatbox applications
- Built with Angular framework

---

Made with ❤️ by theQuarky
