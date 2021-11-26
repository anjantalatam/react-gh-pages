### Here is how you can deploy your React App on GitHub

1. Install gh-pages `npm i gh-pages`
2. Now make these changes in your package.json file
3. Add `"homepage":"https://<your-github-username>.github.io/<name-of-repo>"` <br> <br><img width="669" alt="homepage" src="https://user-images.githubusercontent.com/53368431/143556335-dd0eb962-8fae-48e8-9c0e-64eac39be2d1.png" />
4. Add scripts 
    - `"predeploy": "npm run build"`
    - `"deploy": "gh-pages -d build"` <br><br><img width="465" alt="scripts" src="https://user-images.githubusercontent.com/53368431/143557983-1db39c64-7c55-455f-9f0a-47911c890c29.png">
5. Go to the terminal or command-prompt and run `npm run deploy`
6. You should see `Published` after few seconds. <br><br>  <img width="358" alt="Published" src="https://user-images.githubusercontent.com/53368431/143560135-6ed23fff-1dba-4138-a398-1cb251bc1444.png">
7. Now your website is live on `https://<your-github-username>.github.io/<name-of-repo>` 
  <br> https://anjantalatam.github.io/react-gh-pages
