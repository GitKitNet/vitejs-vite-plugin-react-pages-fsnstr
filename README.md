# vitejs-vite-plugin-react-pages-fsnstr

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/vitejs-vite-plugin-react-pages-fsnstr)

npm install -g wrangler

# Recommended!
npm create astro@latest

# Manual:
npm install --save-dev astro

import { transform } from '@astrojs/compiler';

const result = await transform(source, {
  site: 'https://mysite.dev',
  sourcefile: '/Users/astro/Code/project/src/pages/index.astro',
  sourcemap: 'both',
  internalURL: 'astro/internal',
});