<p align="center">
  <a href="https://suyundukov.com">
    <img src="https://img.shields.io/website/https/suyundukov.com.svg">
  </a>
</p>

## What's it?

This repo contains source code for [my personal website][website]. All the stuff is processed and deployed on [this site][website].

## How to run the site locally?

Before you get started make sure you have an up-to-date version of Go and Node. I use [Homebrew][brew] for all this thingies:

```bash
$ brew install go
$ brew install node
```

Then, clone this repo by running:

```bash
$ git clone https://github.com/suyundukov/suyundukov.com.git
```

We need [Hugo][hugo], to generate `.html` files. You cand get it by running:

```bash
$ go get -u github.com/spf13/hugo
```

or using `brew`:

```bash
$ brew install hugo
```

Now we can install all necessary `node` modules:

```bash
$ npm install
```

Now we should be able to generate all `.html` files and process all `.scss` files. We can do it by running:

```bash
$ hugo && npm run build
```

Normally, that's all. All necessary files for running this site locally are now in `public` folder.

## Thanks 👏
The site use many tools and services to stay alive 🤘
- [GitHub][github], all the data is generously hosted on :octocat:;
- [Git][git], 📦 blogs, codes, files version control system;
- [Markdown][md], a 🌺 beautiful and ❄️ lightweight markup language;
- [Google][google], :squirrel: the one who tell me how to make it
- And many other cool stuff



[brew]: https://brew.sh
[firebase]: https://firebase.google.com
[github]: https://github.com
[git]: https://git-scm.com
[google]: https://google.com
[md]: https://daringfireball.net/projects/markdown/
[travis]: https://travis-ci.org
[website]: https://suyundukov.com
