# Hosting

Finding somewhere to put your thing—whatever it is—can be a pain. I don't want to manage servers if I can help it, so accordingly, I'm a big fan of this movement towards [serverless architectures](https://en.wikipedia.org/wiki/Serverless_computing). Obviously there are still servers, but when someone else is managing them \(often for free if your project is small enough, and usually very affordably if it starts to get bigger\) it feels like there aren't.

* [Netlify](https://www.netlify.com/) is one of my favourite options for personal projects. It has a generous free option.
* For quick deploys of any old static stuff to the internet [surge.sh](https://surge.sh/) and [now.sh](https://zeit.co/now) are both convenient options.
* [Google](https://cloud.google.com/products/) has an extensive offering of hosting services, including functions and static hosting. These might be worth considering, especially if you need [database hosting](data-collection/#databases) too.
* For something more fully fledged or involving self-hosting multiple services, give Docker combined with a container hosting platform like [Digital Ocean](https://www.digitalocean.com/) a go.
* [nginx-proxy](https://github.com/jwilder/nginx-proxy) is a nice little container for running multiple web-facing docker services on a single server. It's essentially a reverse proxy which routes requests to the correct container.

## Live coding environments

These may not strictly be hosting services, but they can be incredibly useful in similar ways.

* [RunKit](https://runkit.com/) is a free live coding environment for Node.js which can also be used for [creating simple APIs or lambda functions](https://runkit.com/docs/endpoint).
* [Glitch](https://glitch.com/) is a pretty handy space for Node.js experiments too. And bonus\(!\) projects there offer [data persistence](https://glitch.com/storage).
* [Observable](https://observablehq.com/) is a pretty unique live coding offering particularly suitable for visualisations from the god of D3, Mike Bostock.

