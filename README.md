Example project for https://stackoverflow.com/questions/53885107/typescript-cant-find-module-flatpickr-even-though-it-includes-typescript-types

Run `yarn run tsc --project .` to replicate the issue.

```
test.ts:1:23 - error TS2307: Cannot find module 'flatpickr'.

1 import flatpickr from "flatpickr";
                        ~~~~~~~~~~~


Found 1 error.

error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
