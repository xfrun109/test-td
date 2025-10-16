## Description
Please include a summary of the changes and the related issue. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes # (issue)

### Type of change
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

## Screenshots
*This is optional.*

### Checklist
*Please add reason for optional check. (eg. Not applicable)*

- [ ] I have followed the code style guidelines of the project.
- [ ] I have performed a self-review of my code
- [ ] I have written a short summary that describes the change.
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have linked working item/s.
- [ ] I have added/updated unit tests [optional]
- [ ] I have added data-senses tags for e2e [optional]
- [ ] I have removed unnecessary `console.logs`
- [ ] I have made corresponding changes to the documentation
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged/published/deployed in downstream modules (external API, DB changes, etc)

### Coding convention & best practices
- Use `camelCase` in general.
- Use `UPPER_SNAKE_CASE` for constants.
- Use descriptive variable & function name.
- Prefix with `is` boolean type variable/function name.
- Suffix with `$` observable type variable/function name.
- Use `const`, `let` for reassigned variables.
- Prefere constants instead of magic values (hardcoding) to increase reusability (eg. `if(a === '123')` vs `if(a === CONST_123)`).
- Use optional chaining (eg. `x?.subX`).
- Use strict equality and inequality operators (eg. `===` or `!==`).
- Use shortcut for boolean tests (eg: `if(x)` vs `if(x === true)`).
- Use `async` pipe whenever is possible.
- Avoid memory leaks (eg: `dont forget to unsubscribe`).

### Best practices unit test
- Use spectator library.
- Use `jest.spyOn` for spy.
- Use `jest.useFakeTimers().setSystemTime(new Date('2020-01-01'))` for faking timers.
- Use snapshot testing for html rendering.
- Use `jest.restoreAllMocks()` for clearing mocks.

### Team Depo Innovators PR Template
