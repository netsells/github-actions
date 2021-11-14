# Github Actions for Frontend Projects

This repository contains composite actions used on frontend projects in the Netsells Organisation.

## Available Composite Actions

- [Visual Regression Testing](./visual-regression-testing)
- [Tests](./tests)
- [Eslint (Reviewdog)](./reviewdog-eslint)
- [Stylelint (Reviewdog)](./reviewdog-stylelint)

## Contributing

Additional actions can be added or modified until there are breaking changes. Breaking changes require creating a new "version". 

Versions for these actions are branch based, e.g. `uses: netsells/github-actions-frontend/visual-regression-testing@v2` would reference the `v2` branch.

Updates should always be mirrored on the `main` branch and a new version released by creating a branch off of main with the new vesion number if required. `main` should be considered latest and stable, whereas the version branches should indicate a non-breaking state of the action.
