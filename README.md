# patricknasser.com.br

Personal site of Patrick Nasser — Senior Data Scientist, MSc Statistics / BSc
Economics (USP).

Built with [Hugo](https://gohugo.io) + [Hugo Blox](https://hugoblox.com).
Deployed via Netlify.

## Local development

Requirements: Hugo extended ≥ 0.161, Go ≥ 1.21, Node ≥ 22, `pnpm`.

```bash
pnpm install
hugo server -D
```

Then open <http://localhost:1313>.

To produce a production build locally:

```bash
hugo --gc --minify
pnpm run pagefind
```

Output goes to `public/`.

## License

Site content © Patrick Nasser. Theme released under the MIT License — see
[LICENSE.md](LICENSE.md).
