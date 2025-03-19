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
