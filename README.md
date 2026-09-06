# `.github`

Organization-wide defaults for [Vorluno](https://vorluno.dev). GitHub applies the files here to
**every repository in the organization that does not carry its own copy** — so a repository created
tomorrow starts with a security policy, a code of conduct and a contribution guide already in place,
instead of getting them whenever someone remembers.

| File | Applies to |
|---|---|
| `SECURITY.md` | Every repository without its own. The 72-hour acknowledgement is the one response time we commit to. |
| `CODE_OF_CONDUCT.md` | Every repository without its own. |
| `CONTRIBUTING.md` | Every repository without its own. Repositories that are demonstrations rather than packages override it. |
| `profile/README.md` | The organization's public front page. |

Repositories that need to say something different say it in their own copy; the file in the
repository always wins over the one here.
