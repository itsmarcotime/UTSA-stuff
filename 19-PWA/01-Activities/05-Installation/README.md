# 🏗️ Implement a Manifest.json File with webpack

Work with a partner to implement the following user story:

* As a developer, I want to be able to automatically generate a `manifest.json` file inside `dist` when I run my application to make my application installable.

## Acceptance Criteria

* It is done when the `webpack-pwa-manifest` is installed as a devDependency.

* It is done when a new `WebpackPwaManifest` plugin is included in the `webpack.config.js` file.

* It is done when the `WebpackPwaManifest` plugin takes an object as a parameter with the following keys: `name`, `short_name`, `description`, `background_color`, `theme_color`, `start_url`, `publicPath`, and `icons`.

* It is done when the `manifest.json` file is generated when I build my application.

* It is done when I can install my application as a Progressive Web App.

* It is done when I can inspect my `manifest.json` file generated using Chrome DevTools.

## 📝 Notes

Refer to the documentation:

[Webpack PWA Manifest plugin documentation](https://www.npmjs.com/package/webpack-pwa-manifest)

---

## 💡 Hints

How could our JSON be represented in a JavaScript object?

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* What is each key in a `manifest.json` file responsible for?

Use [Google](https://www.google.com) or another search engine to research this.

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
