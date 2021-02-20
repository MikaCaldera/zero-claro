Zero Point
---

### An efficient Eleventy starter to get you up to zero and start working.

A lightweight [Eleventy](https://11ty.io) starter kit with [Netlify CMS](https://www.netlifycms.org/).

## Features

Zero Point version 1.0 features:

✍️ A pre-configured [Netlify CMS](https://www.netlifycms.org/)  
🔑 Role-based access control with [Netlify Redirects](https://docs.netlify.com/routing/redirects/)  
🎨 Customisable design tokens  
🌍 Customisable global data and navigation  
✅ Progressively enhanced, semantic and accessible  
🚰 Sass powered CSS system  
⚙️ Service worker that caches pages so people can read your articles offline  
📱 Progressive Web App  
🚀 Optional RSS feed for posts  
💌 Ready for [Netlify Forms](https://docs.netlify.com/forms/setup/#html-forms)

---

## Terminal commands

### Serve the site locally

```bash
yarn start
```

### Build a production version of the site

```bash
yarn production
```

### Compile Sass

```bash
yarn sass:process
```

### Re-generate design tokens for Sass

```bash
yarn sass:tokens
```
### Package site for delivery
Remove cms and other artifacts for delivery to a client or 3rd party host.

```bash
yarn deliver
```

---

**Note**: _Credit must be given to the hard work [Jina Anne](https://twitter.com/jina) did in order for the concept of design tokens to even exist. You should watch [this video](https://www.youtube.com/watch?v=wDBEc3dJJV8), then [read this article](https://the-pastry-box-project.net/jina-bolton/2015-march-28) and then sign up for [this course](https://aycl.uie.com/virtual_seminars/design_tokens_scaling_design_with_a_single_source_of_truth) to expand your knowledge._

---

To change the design tokens in the CMS, find the “Globals” in the sidebar then in the presented options, select “Theme Settings”.

To change the design tokens directly, edit [`_src/data/tokens.json`](https://github.com/hankchizljaw/hylia/blob/master/src/_data/tokens.json).

The tokens are converted into maps that the Sass uses to compile the front-end CSS, so make sure that you maintain the correct structure of `tokens.json`.
