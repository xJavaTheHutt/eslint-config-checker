# eslint-config-checker

Checks [ESLint](https://eslint.org/docs/rules/) configuration file for outdated or redundant
rules, or to give suggestions on parser options, environments, extending, plugins or optional
arguments for rules.

### Current Features

- Checks deprecated rules
- Checks removed rules
- Checks ECMAScript 6 rules
- Check if eslint:recommended options are explicitly in rules

### Upcoming Features

- Error handling
- Check parser options, env, extends and plugins objects
- Check if rule's value is the default
- Add other file types
- Print out additional optional options
- Recommended adding "eslint:recommended" if a recommended rule is found
