# WebProject-Essentials
The listing of the personal web projects' basic files and initial tasks

# HTML

# CSS
Use [CSS_Reset.css](./CSS_Reset.css) for clean environment.\
But **don't forget you are using that CSS file if you apply it.** ⚠️

# JS

# Vue
## Installation
- Check the node version (use LTS version), install new one if needed.
- `npm install @vue/cli`
- `vue create PROJECT_NAME` (Use this instead of `npm init`.)

## Basic setting
- Check the vue version. Make sure the version definition in package.json is starting with wildcard `^` or `~`. (`^` is recommended.)
- Turn off `"no-unused-vars"` and `"no-undef"`. (package.json > eslint rules > set them as `"off"` or `"warn"`)
- Set git remote url. `git remote add origin URL`
- Change local branch name to `main` (`master` is the default name)
- Push forcibly to origin\main branch to clean git history. `git push origin main -f`
