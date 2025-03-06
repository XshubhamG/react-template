# React Template using tailwindCSS

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [CLI Flags](#cli-flags)

## description

This is a react template using tailwindCSS.It is a simple template to get started with React and tailwindCSS.

## installation

```bash
bun create xshubhamg/react-template <directory_name>

# OR

bun create github.com/xshubhamg/react-template <directory_name>
```

## Dependencies

- [vite](https://vitejs.dev/)
- [tailwindcss](https://tailwindcss.com/)
- [prettier](https://prettier.io/)
- [eslint](https://eslint.org/)
- [prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)

The above `bun create` command will create a new directory with the name of your choice.And initialize
a new react project in that directory using vite and tailwindCSS preconfigured. You can now start
developing your project.
You can use `bun run dev` to start the development server.Optionally specify a name for the destination
folder. If no destination is specified, the repo name will be used.

## Usage

Create a new directory with the name of your choice. Provide that directory name in the above `bun create`
command in place of `<directory_name>`.

Bun will perform the following steps:

- Download the template
- Copy all template files into the destination folder
- Install dependencies with `bun install`.
- Initialize a fresh Git repo. Opt out with the `--no-git` flag.
- Run the template's configured `start` script, if defined.

## CLI Flags

| Flags          | Description                                          |
| -------------- | ---------------------------------------------------- |
| `--force`      | Force creation even if the directory already exists. |
| `--no-git`     | Skip initializing a new Git repo.                    |
| `--no-install` | Skip installing `node_modules` & tasks.              |
| `--open`       | Start & open in-browser after finish                 |

## Author

- GitHub: [xshubhamg](https://github.com/xshubhamg)
- Twitter: [@xshubhamg](https://twitter.com/codin_nerd)`
