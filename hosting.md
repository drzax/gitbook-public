# Hosting

Finding somewhere to put your thing—whatever it is—can be a pain. I don't want to manage servers if I can help it, so accordingly, I'm a big fan of this movement towards [serverless architectures](https://en.wikipedia.org/wiki/Serverless\_computing). Obviously there are still servers, but when someone else is managing them (often for free if your project is small enough, and usually very affordably if it starts to get bigger) it feels like there aren't.

* [Netlify](https://www.netlify.com/) and [Vercel](https://vercel.com/) my favourite options for personal projects. They both have generous free tiers and straight forward continuous deployment from GitHub.
* For quick deploys of any old static stuff to the internet [surge.sh](https://surge.sh/) is convenient.
* [Google](https://cloud.google.com/products/) has an extensive offering of hosting services, including functions and static hosting. These might be worth considering, especially if you need [database hosting](data-collection/#databases) too.
* [Supabase](https://supabase.com/) started out as a hosted database solution based on Postgres and focussed on integration with cloud hosting. It has evolved into a product suite including authentication, storage and edge functions.
* For something more fully fledged or involving self-hosting multiple services, give Docker combined with a container hosting platform like [Digital Ocean](https://www.digitalocean.com/) a go.
* [nginx-proxy](https://github.com/jwilder/nginx-proxy) is a nice little container for running multiple web-facing docker services on a single server. It's essentially a reverse proxy which routes requests to the correct container.
* [Carrd](https://carrd.co/) is a lean hosted CMS for simple one page sites.

## Content management, frameworks, static site generators, etc

* [SvelteKit](https://kit.svelte.dev) — my site builder of choice.
* [Blot](https://blot.im/) — a neat idea: turns a plain old folder on your computer into a website.
* [Gatsby](https://www.gatsbyjs.org) — a static site generator built on GraphQL and React.
* [Wordpress](https://wordpress.org)

## Live coding environments

These may not strictly be hosting services, but they can be incredibly useful in similar ways.

* [RunKit](https://runkit.com/) is a free live coding environment for Node.js which can also be used for [creating simple APIs or lambda functions](https://runkit.com/docs/endpoint).
* [Glitch](https://glitch.com/) is a pretty handy space for Node.js experiments too. And bonus(!) projects there offer [data persistence](https://glitch.com/storage).
* [p5.js](https://p5js.org/) is a live coding environment and set of javascript libraries based of the [Processing](https://processing.org/) framework and great for highly visual interactive coding experimentation.&#x20;
* [Observable](https://observablehq.com/) is a pretty unique live coding offering particularly suitable for visualisations from the god of D3, Mike Bostock.
  * [Observable is not Javascript](https://observablehq.com/@observablehq/observables-not-javascript) — a brief look a the differences.
  * The [Observable Standard Library](https://github.com/observablehq/stdlib/blob/master/README.md) (and [examples](https://observablehq.com/@observablehq/standard-library)).
