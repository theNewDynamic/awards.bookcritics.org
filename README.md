The only thing different from one starter repo to another is the layouts folder and sample content.

For now, we need to add these (they are not a part of the repo because submodules are a pain if you don't want them)

git submodule add https://github.com/theNewDynamic/hugo-base-layouts.git themes/hugo-base-layouts

git submodule add https://github.com/theNewDynamic/hugo-base-components.git themes/hugo-base-components


tools
 - [Webpack 3+](https://webpack.js.org/) _probably 4 soon_
 - Prettier (code formatting, wip)
 - PostCSS | [TailwindsCSS](https://tailwindcss.com/) (library of JS-based CSS classes ) | [PurgeCSS](https://www.purgecss.com/) (removes unused CSS)
 - JS: [Turbolinks](https://github.com/turbolinks/turbolinks) (HTML5 History API for faster navigation)
 - JS: [Lazysizes](https://github.com/aFarkas/lazysizes) (lazy asset loading)
 - [KyleAMathews/typefaces](https://github.com/KyleAMathews/typefaces) (load OS fonts locally with one little `require`)

 layouts
 - layouts = starter files for specific site styles (separate repos)
 - themes/tnd-base = base files
 - themes/tnd-components = reference files that can be copied into src/layouts
