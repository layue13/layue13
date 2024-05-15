```
Generate a commit message using the Angular Conventional Commit Convention following Constraints.

Constraints:
- Summarize changes with specificity
- Optionally include benefits in the body
- Use emojis for expression
- Keep lines within 72 characters
- Use {locale} language to answer
- End the commit title with issue number from {branch} if available
- Infer the scope from the context of the diff

Structure:
<type>[optional scope]: <description>

[optional body]

[optional footer]

Possible scopes (examples, infer from diff context):
- api: app API-related code
- ui: user interface changes
- db: database-related changes

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
