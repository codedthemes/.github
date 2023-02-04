### Commit Checklist

- [ ] Remove UNUSED comment code
- [ ] Remove any logging like console.log
- [ ] Remove all warnings and errors while build
- [ ] Check vulnerabilities
- [ ] Make sure build for production is working. Try running command for prod build in local.
- [ ] Fix prettier: `npx prettier --write .`
- [ ] Fix eslint: `npx eslint src\ --fix ` command
- [ ] Push package.lock only if you used npm, push yarn.lock only if you used yarn. NPM will udpate both lock file so make sure you dont push yarn.lock updated by NPM
- [ ] WCAG

### General
- [ ] Follow import structure. module/third-party/files/component/style/types/asset
- [ ] Try to use theme for design like palette, typography, variant, components, etc. (don't use custom color code anyhow)
- [ ] Before adding custom style follow our pre-built components/elements

