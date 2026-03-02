# SMASH

### Stack
- Hugo
- Tailwind
- Netlify

### Local install
1. `npm install`
2. `brew install hugo`
3. `hugo server --disableFastRender`

### Adding content
- Existing pages can be edited under `/content`
- Adding a new page requires creating a new `.md` file under `/content` and adding a new `[menu]` item in `hugo.toml`

### Deploy
Auto deployments are set up pointing to the main branch. Once your work is ready, merge it in and wait.

### References
- Hugo: https://gohugo.io/
- Folder structure explained: https://gohugo.io/getting-started/directory-structure/
- Tailwind docs: https://tailwindcss.com/docs/installation