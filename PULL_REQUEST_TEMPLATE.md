### Commit Checklist

- [ ] Remove UNUSED comment code
- [ ] Remove any logging like console.log
- [ ] Remove all warnings and errors while build
- [ ] Make sure build for production is working. Try running command for prod build in local.
- [ ] Fix prettier: `npx prettier --write .`
- [ ] Fix eslint: `npx eslint src\ --fix ` command
- [ ] Push package.lock only if you used npm, push yarn.lock only if you used yarn. NPM will udpate both lock file so make sure you dont push yarn.lock updated by NPM

### General
- [ ] Follow import structure. module/third-party/files/component/style/types/asset
- [ ] Follow project directory structure
- [ ] To create any new page follow our sample page or any other page
- [ ] Try to use theme for design like palette, typography, variant, components, etc. (don't use custom color code anyhow)
- [ ] Before adding custom style/sx follow our pre-built components/elements (use the minimum number of sx styles)
- [ ] For the main section use the Grid component and for the sub-section - use the Stack component
- [ ] Check all files changed by you in vs code and only commit needed once
- [ ] When you rename file or directory, use the command code (don't rename pushed files manually)
