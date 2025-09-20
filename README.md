# 🎬 Anime Filter

A sleek React application that intelligently filters your anime list, removing duplicates and excluding movies, OVAs, specials, and other non-series content. Perfect for organizing your anime collection.

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-Animations-1572B6?logo=css3&logoColor=white)
![Netlify](https://img.shields.io/badge/Deployment-Netlify-00C7B7?logo=netlify&logoColor=white)

## Getting Started

First, install the dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the app by modifying `src/App.jsx`. The page auto-updates as you edit the file.

## How to Use

1. **Upload your anime list**: Click "Choose File" or drag and drop your file
2. **Supported formats**: TXT, HTML, or XML files
3. **Automatic filtering**: The app will remove duplicates, movies, OVAs, and specials
4. **Copy your results**: Use the "Copy to Clipboard" button to save your cleaned list

## How It Works

The app uses a smart filtering algorithm that:
- Removes duplicate entries
- Excludes movies, OVAs, specials, recaps, and ONAs
- Keeps only unique series titles
- Processes everything in your browser (your data never leaves your device)

## Deployment

The easiest way to deploy this React app is to use [Netlify](https://netlify.com).

1. Build the production version:
```bash
npm run build
```

2. Drag and drop the `build` folder to [Netlify](https://netlify.com)

Your app will be live with a free Netlify subdomain (like `your-app-name.netlify.app`).

## Technologies Used

- **React** - UI framework
- **CSS3** - Styling with animations
- **HTML5 File API** - File processing
- **Canvas API** - Background animations

## Learn More

To learn more about React, check out the following resources:

- [React Documentation](https://reactjs.org/docs/getting-started.html) - learn about React features and API
- [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started) - learn more about Create React App

You can also check out the [React GitHub repository](https://github.com/facebook/react) - your feedback and contributions are welcome!

## License

This project is licensed under the MIT License.
