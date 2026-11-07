# Angular Prettier

Source code used in the article [Configure Prettier with Angular](https://blouppy.com/blog/2023-01-29-configure-prettier-with-angular/) on the [Blouppy](https://blouppy.com) website.

It is a new Angular 22 application (`ng new`) with a team-wide [Prettier](https://prettier.io/) configuration:

- `.prettierrc`: the formatting options, with an `overrides` entry that formats `*.html` with the `angular` parser (control flow such as `@if` and `@for` included).
- `.prettierignore`: the build output, the Angular cache and the lock file.
- Two npm scripts: `format-check` (`prettier --check .`) and `format` (`prettier --write .`).

## Project version

- Angular 22. This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 22.2.6.
- Node.js 22 (an active or maintenance LTS version supported by Angular 22).

## NPM packages included

- **prettier**: 3.9.10

## Run it

```bash
npm ci
npm run format-check   # check the formatting
npm run format         # format every file
npm start              # ng serve on http://localhost:4200
npm run build          # production build in dist/
```

## Give a Star! :star:

If you like or are using this project please give it a star. Thanks!

## Support this project! :pray:

If you want to help me to maintain this project or add improvements, it would be a pleasure!
