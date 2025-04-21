# trenton-gill-camp-site
npx create-react-app trenton-gill-camp-site
cd trenton-gill-camp-site
npm install gh-pages --save-dev
"homepage": "https://your-username.github.io/trenton-gill-camp-site"
"scripts": {
  "start": "react-scripts start",
  "build": "react-scripts build",
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
git init
git remote add origin https://github.com/your-username/trenton-gill-camp-site.git
git add .
git commit -m "Initial commit"
git push -u origin main
npm run deploy
