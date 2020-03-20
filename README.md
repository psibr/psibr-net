# 卩丂丨乃尺 .NET website & docs

[卩丂丨乃尺](https://github.com/psibr) is a .NET OSS organization.

This is the website hosted at [psibr.net](https://www.psibr.net)

## Cloning the website and docs

The following will give you a project that is set up and ready to use (don't forget to use `--recurse-submodules` or you won't pull down some of the code you need to generate a working site). The `hugo server` command builds and serves the site. If you just want to build the site, run `hugo` instead.

```bash
git clone --recurse-submodules --depth 1 https://github.com/psibr/psibr-net.git
cd psibr-net
hugo server
```

The [theme](https://github.com/psibr/docsy-example) is included as a Git submodule:

```bash
▶ git submodule
 a053131a4ebf6a59e4e8834a42368e248d98c01d themes/docsy (heads/master)
```
dasdas
If you want to do SCSS edits and want to publish these, you need to install `PostCSS` (not needed for `hugo server`):

```bash
npm install
```

## Running the website locally

Once you've cloned the site repo, from the repo root folder, run:

```
hugo server
```
