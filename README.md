<div>
  <img src="src-tauri/icons/icon.ico" width=256 height=256>
  <img src="src/assets/svelte.png" width=256 height=256>
</div>

# Tauri app with a Svelte frontend

This repository is meant to be a barebones example of a [Tauri](https://tauri.app) app using the [Svelte](https://svelte.dev/) frontend. 

If as a beginner to Svelte - or, more likely, to Tauri - your first app encounters issues, you can use this repository as a reference point for an application that works. Understanding the code present in this repository can be a good first step towards building a Tauri app, along with following the [Tauri guides](https://tauri.app/v1/guides/).

I also made this repository for my personal use as a template.

## Reproduction steps
Note that instead of cloning this repository, you can reproduce it by following those steps:

- [Install all the prerequisites to working with Tauri](https://tauri.app/v1/guides/getting-started/prerequisites)
- In the parent directory of your choice, run `npm create tauri-app`
- Fill in the name of your app and the title of the main window of your app
- Select `create-vite` as your UI recipe
- Add the "@tauri-apps/api" npm package
- Select `svelte-ts` as your vite template
- Go into your folder, and modify the following files:
  - In `src-tauri.tauri.conf.json` change the `"identifier"` parameter (intially set as `"com.tauri.dev"`) to something else, of your choice
  - In `src-tauri.tauri.conf.json` change the `"distDir"` parameter (intially set as `"../dist"`) to `"../public"`

You are now ready to experiment with the incredibly promising framework that is Tauri, with the best frontend out there (😉), Svelte!

## See Also

If after these steps you feel like making your life even easier, add [Tailwind CSS](https://tailwindcss.com/) to your project following steps 2 to 5 of [these instructions](https://tailwindcss.com/docs/guides/vite). Now you can even write beautiful styles super fast!

Note that installing Tailwind come with the risk of annoying CSS purists.

