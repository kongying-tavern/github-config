# Kongying Tavern Github Config

This is Kongying Tavern github repository configuration.

## Features

- ❤️ [Sponsor](.github/FUNDING.yml)
- 🤖 [DependaBot](.github/dependabot.yml)
- 📝 [CommitConvention](.github/commit-convention.md)
- 🦾 [IssuesHelper](.github/workflows/issue-commented.yml)
- ☁️ [GithubPagesCI](.github/workflows/pages.yml)
- 🖊️ [Issues and Pull requests template](.github/ISSUE_TEMPLATE/)

## Checklist

When you use this template, try follow the checklist to update your info properly

- [ ] Modify the branch and paths-ignore in `workflows`
- [ ] Replace or delete discussion items in `.github/ISSUE_TEMPLATE/config.yml`
- [ ] Check whether the script in the workflow matches the one in your project
- [ ] If your package management tool is not pnpm, please refer to `.github/workflows/pages.yml` to modify
- [ ] Add script `"envinfo": "npx envinfo --npmPackages  --system --browsers --binaries --duplicates"` in package.json
- [ ] Change the author name in `LICENSE`
- [ ] Clean up the README and remove CHANGELOG

### GitHub Pages

1. Set the correct base config.

    If you are deploying to `https://<USERNAME>.github.io/`, you can omit this step as `base` defaults to `"/"`.

    If you are deploying to `https://<USERNAME>.github.io/<REPO>/`, for example your repository is at `https://github.com/<USERNAME>/<REPO>`, then set `base` to `"/<REPO>/"`.

## Usage

Copy the `.github` folder to your project root directory

## Thanks

This project is heavily inspired by the following awesome projects.

- [IssuesHelper](https://github.com/actions-cool/issues-helper)
- [ActionSetup](https://github.com/pnpm/action-setup)
- [ActionCatch](https://github.com/actions/cache)
- [Envinfo](https://github.com/tabrindle/envinfo)
- [ConventionalChangelog](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-angular)

## License

[MIT](https://github.com/kongying-tavern/github-config/blob/main/LICENSE)
