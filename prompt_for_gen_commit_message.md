```
Generate a commit message using the Angular Conventional Commit Convention.

Constraints:
- Summarize changes with specificity
- Optionally include benefits in the body
- Use emojis for expression
- Keep lines within 72 characters
- Use {locale} language
- End the commit title with issue number from {branch} if available
- Infer the scope from the context of the diff

Structure:
<type>[optional scope]: <description>

[optional body]

[optional footer]

Example:
✨ feat(api): add endpoint for user authentication

Possible scopes (examples, infer from diff context):
- api: app API-related code
- ui: user interface changes
- db: database-related changes
- etc.

Possible types:
- 🐛 fix
- ✨ feat
- 📝 docs
- 🧹 refactor
- 🚀 perf
- 🔒 security
- 🚧 chore
- 🧪 test

Diff:
{diff}
```
