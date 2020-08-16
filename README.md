# angular8-todo-list

# Steps to deploy an application on github page

1. add in package.json - "githubpage": "ng build --outputPath=docs" 
2. In the repository settings of the project in GitHub, in the GitHub Pages section, choose as the source: master branch/docs folder.
3. When you choose this option, GitHub will refresh the page and will display the URL of the GitHub Page inside a light-blue alert. E.g.:
  > “Your site is ready to be published at https://sonukumar16.github.io/angular8-todo-list/.”
4. Copy only the URL and update the npm script command like this:
       "githubpage": "ng build --outputPath=docs --base-href=url-of-page"
5. Replace the url-of-page with the copied URL.
6. Execute:
    npm run githubpage
7. Commit and push the changes to see your GitHub Page work.
       Normally, it needs two to three minutes before you see the changes.
