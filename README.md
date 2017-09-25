NOTE: This repository is a slightly modified version of the original from the ionic framework team.

Ionic Unit Testing Example
=====================

This repository is an example project that gives guidance on setting up your Ionic application for unit testing and end-to-end (E2E) testing. We have been told the folks at Ionic will be adding testing features to new projects in the future. But until then, feel free to borrow from this project as needed.

Special thanks to all of the contributors. With the exception of the Ionic team's updates to the framework, this project is stable. If you have a suggestion, feel free to update code and make a pull request. Find a problem or bug, feel free to file a detailed issue. 

Getting Started
===============

To get started, clone this repo, and run `npm install` in the root directory.

Unit Tests
----------

To run the tests, run `npm test`.

See the example test in `src/app/app.component.spec.ts` for an example of a component test.

End-To-End Tests (Browser-Only)
-------------------------------

To serve the app, run `ionic serve`.

To run the end-to-end tests, run (while the app is being served) `npm run e2e`.

See the example end-to-end test in `e2e/app.e2e-spec.ts`.
