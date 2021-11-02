<p align="center">
  <img src="src/images/logo_elastic.png" width="60"  alt="Elastic Logo"/>
</p>

<h1 align="center">
  Elastic's Next.js EUI Starter
</h1>

Jump right in to building prototypes with [EUI](https://github.com/elastic/eui).

_🚩 This starter is not constantly maintained and may get out of sync with the latest EUI release._

## 🚀 Super-quick start using CodeSandbox

1. Go to
   [https://codesandbox.io/s/github/elastic/next-eui-starter](https://codesandbox.io/s/github/elastic/next-eui-starter)
   and start editing. CodeSandbox will fork the sandbox when you make
   changes!

## 🚀 Quick start

1.  **Install yarn**

    This starter expects to use [yarn](https://yarnpkg.com/) to manage
    dependencies, so go install it.

1.  **Copy the Next.js starter**

    Clone the repository:

    ```sh
    git clone https://github.com/pejonic/nextjs-eui-starter.git my-eui-starter
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd nextjs-eui-starter/

    # Install depdendencies.
    yarn

    # Optional: start a new git project
    rm -rf .git && git init && git add . && git commit -m "Initial commit"

    # Start the dev server
    yarn dev
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:3000`!

    Open the `my-eui-starter` directory in your code editor of choice and edit `src/pages/index.tsx`. Save your changes and the browser will update in real time!

1. **Deploy your site to GitHub Pages**

    When you're ready to deploy and share your site to GitHub Pages, you can use the provided `yarn build-docs` script to do so. The first time you do this, you need to do some preparation:

    1. (Optional) If you need to, set the `pathPrefix` option in `next.config.js` to reflect the name of your GitHub repo. The starter kit will try to derive this itself, so you're unlikely to see to do anything here.
    1. (Optional) Commit the above change
    1. Create the GitHub pages branch: `git branch gh-pages`

    Then whenever you want to update your site:

    1. Commit any pending changes
    1. Run `yarn build-docs`
    1. Publish the `master` and `gh-pages` branches by pushing them to GitHub: `git push origin master gh-pages`
    1. Edit your repository settings to ensure your repository is configured so that the `gh-pages` branch is used for serving the site. (You only need to do this once, but you have to push the branch before you can change this setting)
    1. Access your site at https://your-username.github.io/repo-name. There
       can be a slight delay before changes become visible.

---


