# Git commit convetions

Conventional commits are a structured way to format and document commit messages in a consistent and meaningful manner. They are helpful in automating tasks like generating changelogs and versioning releases based on commit history.

## Commit Stucture

Conventional commits follow the following structure:
```bash
<type>(<scope>): <message>
```
- `<type>`: Describe the purpose or nature of the commit
- `<scope>`: (optional), specifies the module, component, or area affected by the commit
- `<message>`: A concise and descriptive message about the brought changes.

## Type
The <type> is crucial in conventional commits and helps categorize the nature of the commit. Some commonly used types include:
- `feat`: For new features or enhancements.
- `fix`: For bug fixes.
- `chore`: For maintenance tasks or minor changes that don't affect the main code.
- `docs`: For documentation changes.
- `style`: For code style or formatting changes.
- `refactor`: For code refactoring without adding new features or fixing bugs.
- `perf`: For performance improvements.
- `test`: For adding or modifying tests.

## Example
For example we can take the commit I am about to make to edit this readme:
```bash
docs: edit README to explain commits conventions
```
Here, we are using the `docs` type since we are editing a `README` which is part of the documentation. We do not use the scope since the documentation is global. We give a concise message about our commit.
