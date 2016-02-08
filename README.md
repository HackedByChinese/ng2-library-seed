# Introduction

[![Join the chat at https://gitter.im/HackedByChinese/ng2-library-seed](https://badges.gitter.im/HackedByChinese/ng2-library-seed.svg)](https://gitter.im/HackedByChinese/ng2-library-seed?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/HackedByChinese/ng2-library-seed.svg?branch=master)](https://travis-ci.org/HackedByChinese/ng2-library-seed)

A seed for Angular2 library projects

The purpose of this project is to seed the basic structure for Angular2 libraries/modules you'd like to publish for use in other applications, specifically things like reusable directives, components, pipes, and services. It is _not_ intended as a seed for an application.

It assumes the following opinions:

- Written in TypeScript
- Typings are managed by [typings](https://github.com/typings/typings)
- [Gulp](https://github.com/gulpjs/gulp) for managing project and build tasks
- [Karma](https://github.com/karma-runner/karma) as the test runner
- [Jasmine](http://jasmine.github.io/) for unit tests
- Will be integrated continuously by Travis CI or Appveyor

** This seed project is still under development **

## Getting started

**Note:** Node v4 or later is required.

    # Makes a shallow clone using the most recent revision and sets the remote name to `seed`
    git clone -o seed https://github.com/HackedByChinese/ng2-library-seed.git my-project-name
    cd my-project-name

    # Installs project dependencies
    npm install

    # Build production distribution
    gulp build:dist

    # Build dev
    gulp build:dev

    # Build and test dev
    gulp test

    # Build dev continuously
    gulp build:dev:watch

    # Test dev continuously (does not build changes continuously; run build:dev:watch in another terminal or console window)
    # Note: launches Chrome for runtime debugging
    gulp test:watch


    # Now that the basic is installed, building, and testing, make it yours.
    # Set the `origin` remote to your repository
    git remote add origin https://github.com/MyGitHubUserName/MyRepoName.git

    # Push to your repo and set it as the default upstream for master
    git push -u origin master

## License

MIT
