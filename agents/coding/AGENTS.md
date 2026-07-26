# Global Coding Conventions

## General

- Do not write a comment without justification. If code is self-explanatory, leave it uncommented.
- Do not create small helper functions that are referenced only once. Inline the logic.
- Prefer editing existing files over creating new ones when the change is small.

## Git

- Do not modify the git identity - the identity is set by the User.
- Commits must be in Conventional Commits style and in English.
- Commit messages must:
  - Be in American English.
  - Be a single line. Prefer efficient messages under 120 characters.
  - Be in Conventional Commits style.
    - `fix` user-facing change that fixes a released defect. Triggers a release.
    - `feat` user-facing change that makes an improvement. Triggers a release.
    - `feat!` same as `feat`, but is for new behavior that changes a behavior of an existing feature. Confirm with the User before creating a breaking change commit message.
    - `refactor` an internal change that makes no change in behavior.
    - `ci` an internal change that only impacts CI and does not impact the user.
    - `docs` an internal change that only impacts docs (internal or user-facing).
    - `chore` catch all for all other changes. Typically, if multiple commits are used for a feature, the last commit that enables/fully realizes the feature is marked as `feat` (others, marked as `chore`).

## Testing

- Name tests using `When <condition> then <action> should <expected>` convention.
- Structure tests in Arrange-Act-Assert (AAA) form. Do not add `// Arrange`, `// Act`, `// Assert` comments - use blank lines to separate the sections.
