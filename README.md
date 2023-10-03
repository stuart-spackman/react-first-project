# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Directions that were used for making this page: 

After all code is in the GitHub repository...

1. In vite.config.js add the following line in the correct spot:   
    base: '/react-first-project/',

2. The from command line enter: 
    npm run build

3. Then from command line enter: 
    git add dist -f 

4. Then from command line enter: 
    git commit -m 'adding dist'

5. Then from command line enter: 
    git subtree push --prefix dist origin gh-pages

    