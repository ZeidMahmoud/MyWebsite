# My Personal Website

A minimal and fast personal website built with Hugo using the Bear Blog theme. This website serves as my digital home, featuring various sections for sharing knowledge, projects, and resources.

## 📚 Sections

- **Home** - Welcome page and latest updates
- **About Me** - Professional background and personal introduction
- **Contact** - Ways to reach me
- **Library** - Curated collection of books and reading materials
- **Resources** - Helpful links and learning materials
- **Tools** - Software and tools I recommend
- **Blog** - My thoughts and articles
- **Projects** - Showcase of my work
- **RSS** - Subscribe to updates

## 🚀 Technology Stack

- [Hugo](https://gohugo.io/) - Static site generator
- [Bear Blog Theme](https://github.com/janraasch/hugo-bearblog) - Minimal and fast theme
- No JavaScript - Pure HTML/CSS for maximum performance
- RSS Feed support
# Hugo Installation Guide

## Package Managers

```bash
# Debian/Ubuntu/Linux Mint
sudo apt update && sudo apt install hugo

# Arch Linux/Manjaro
sudo pacman -S hugo

# Fedora
sudo dnf install hugo

# openSUSE
sudo zypper install hugo

# CentOS/RHEL
sudo yum install hugo

# Alpine Linux
sudo apk add hugo

# FreeBSD
sudo pkg install hugo

# OpenBSD
sudo pkg_add hugo

# Slackware
sbopko -i hugo 
"install first sbopkg on slackware"

# Using Go (Universal)
go install github.com/gohugoio/hugo@latest

# Using Snap (Universal)
sudo snap install hugo

# Verify Installation
hugo version
```
2. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/hugo-bearblog.git
cd hugo-bearblog
```

3. Start the development server:
```bash
go to exampleSite/ and type "hugo server --source ./exampleSite --themesDir ../.."
```

4. Visit `http://localhost:1313` in your browser

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
<<<<<<< HEAD
# Hugo ʕ•ᴥ•ʔ Bear Blog ![Test](https://github.com/janraasch/hugo-bearblog/workflows/CI/badge.svg?branch=master&event=push)

🧸 A [Hugo](https://gohugo.io/)-theme based on [Bear Blog](https://bearblog.dev).

> Free, no-nonsense, super-fast blogging.

## Demo

For a current & working demo of this theme, please check out https://janraasch.github.io/hugo-bearblog/ 🎯.

## Screenshots

⬜️ [Light][light-screenshot]

⬛️ [Dark][dark-screenshot]

When the user's browser is running »dark mode«, the dark color scheme will be used automatically. The default is the light/white color scheme. Check out the [`style.html`](https://github.com/janraasch/hugo-bearblog/blob/master/layouts/partials/style.html)-file for the implementation.

## Installation

If you already have a Hugo site on your machine, you can simply add this theme via

```bash
git submodule add https://github.com/janraasch/hugo-bearblog.git themes/hugo-bearblog
```

Then, adjust the `hugo.toml` as detailed below.

For more information, read the official [setup guide][hugo-setup-guide] of Hugo.

## Adjust configuration / hugo.toml

Please check out the [hugo.toml](https://github.com/janraasch/hugo-bearblog/blob/master/exampleSite/hugo.toml) included in the [exampleSite](https://github.com/janraasch/hugo-bearblog/tree/master/exampleSite) of this theme.

## Content & structure

### Starting fresh

If you are starting fresh, simply copy over the contents of the `exampleSite`-directory included in this theme to your source directory. That should give you a good idea about how things work, and then you can go on from there to make the site your own.

### Adding / editing content

#### Index-Page

The contents of the `index`-page may be changed by editing your `content/_index.md`-file.

#### Page

You can add **a new page** via running

```bash
hugo new my-new-page.md
```

#### Blog-Post

You can add **a new blog-post** via running

```bash
hugo new blog/my-new-post.md
```

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag, *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Check out the [`style.html`](https://github.com/janraasch/hugo-bearblog/blob/master/layouts/partials/style.html)-file to find out which CSS-styles are applied by default.

## Issues / Feedback / Contributing
Please use [GitHub issues](https://github.com/janraasch/hugo-bearblog/issues) and [Pull Requests](https://github.com/janraasch/hugo-bearblog/pulls).

## Development
Run the `exampleSite` locally via

```bash
hugo server --source ./exampleSite --themesDir ../..
```

## Special Thanks 🎁

A special thank you goes out to [Herman](https://herman.bearblog.dev), for creating the original [ʕ•ᴥ•ʔ Bear Blog](https://bearblog.dev/).

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License) © [Jan Raasch](https://www.janraasch.com)

[hugo-setup-guide]: https://gohugo.io/getting-started/installing
[light-screenshot]: https://raw.githubusercontent.com/janraasch/hugo-bearblog/master/images/screenshot.png
[dark-screenshot]: https://raw.githubusercontent.com/janraasch/hugo-bearblog/master/images/screenshot-dark.png
=======
>>>>>>> 4dbbf3c37c07ac9ddb8f8060e1997862678bedef
