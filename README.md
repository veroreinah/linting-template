# linting-template

Basic linting and files formatting for TypeScript projects.

## HUSKY

```
npm install husky --save-dev
```

Using **husky** to add pre-commit hook that checks if all Prettier and TSLint rules are ok.

If you want to skip pre-commit hook, you should add `--no-verify` flag when committing your work.

## PRETTIER

```
npm install prettier --save-dev
```

**Check prettier files format:** `npm run prettier-check`

**Format files:** `npm run prettier-format`

- Ignore files
  https://prettier.io/docs/en/ignore.html

## TSLINT

```
npm install tslint --save-dev
```

**Check tslint rules:** `npm run tslint-check`

- Recommended rules
  https://github.com/palantir/tslint/blob/master/src/configs/recommended.ts
- TSLint Rules https://palantir.github.io/tslint/rules/

## CODELYZER

```
npm install codelyzer --save-dev
```

A set of tslint rules for static code analysis of Angular TypeScript projects.

- https://www.npmjs.com/package/codelyzer
- Recommended rules https://github.com/mgechev/codelyzer#recommended-configuration
