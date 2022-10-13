# 📖 Use Workbox to Generate a Service Worker

  Work with a partner to implement the following user story:

* As a developer, I want to be able to precache assets so that my app can be viewed even when offline.

## Acceptance Criteria

* It is done when logic is added to the `index.js` to register a service worker.

* It is done when the `webpack.config.js` file is updated to use the `GenerateSW` class of the `workbox-webpack-plugin`.

* It is done when the app is started using `npm install` and `npm run start:dev` and a log from `GenerateSW` appears in the console with a message similar to the following: `“The service worker at service-worker.js will precache 5 URLs, totaling 35.1 kB.”`

* It is done when a `service-worker.js` file is generated in the `build` directory.

* It is done when the service worker is active and the app is still visible even when offline.

## 📝 Notes

Refer to the documentation:

* [Workbox docs on generating a service worker with webpack using GenerateSW](https://developers.google.com/web/tools/workbox/guides/generate-service-worker/webpack)

* [Workbox docs on GenerateSW](https://developers.google.com/web/tools/workbox/reference-docs/latest/module-workbox-webpack-plugin.GenerateSW)

* [Simulate offline behavior with Chrome DevTools](https://web.dev/learn/pwa/tools-and-debug/)

* [Interact with service workers with Chrome DevTools](https://web.dev/learn/pwa/service-workers/)

## 💡 Hints

* How can we use Chrome DevTools to test if our service worker is active and our app is still visible even when offline?

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* Why don't JavaScript modules work inside service workers?

Use [Google](https://www.google.com) or another search engine to research this.

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
