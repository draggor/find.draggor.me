# Lynx

Lynx is designed to be a simple links page powered by [Hugo](https://gohugo.io). It's built using Tailwind CSS and inspired by services like LinkTree.

🌏 [Demo site](https://jpanther.github.io/lynx/)  
🐛 [Bug reports & issues](https://github.com/jpanther/lynx/issues)  
💡 [Questions & feature requests](https://github.com/jpanther/lynx/discussions)

![Screenshot](https://raw.githubusercontent.com/jpanther/lynx/stable/images/screenshot.png)

## Features

- Built with Tailwind CSS JIT for minified stylesheets without any excess code
- Fully responsive layout
- Dark mode (auto-switching based upon browser)
- SVG icons from FontAwesome 5
- HTML and Emoji support
- Fathom Analytics and Google Analytics support
- Favicons support

---

## Installation

Lynx supports several installation methods - as a Hugo Module (easiest), a git submodule, or as a completely manual install.

Below is a quick start guide using Hugo modules.

### Quick start using Hugo

> **Note:** Ensure you have **Go** and **Hugo** installed, and that you have created a new Hugo project before proceeding.

1. From your project directory, initialise Hugo Modules:

   ```shell
   hugo mod init github.com/<username>/<repo-name>
   ```

2. Create `config/_default/module.toml` and add the following:

   ```toml
   [[imports]]
   path = "github.com/jpanther/lynx"
   ```

3. Start your server using `hugo server` and the theme will be downloaded automatically.

4. In the root folder of your website, replace the `config.toml` file that was generated by Hugo with the one from Lynx. You will find the theme config file in the Hugo cache directory, or [download a copy](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/jpanther/lynx/tree/stable/config.toml) from GitHub.

5. Edit the settings in the `config.toml` file to suit your needs. You can also create a `content/_index.md` file to add additional text to your site.

### Installing theme updates

As new releases are posted, you can update the theme using Hugo. Simply run `hugo mod get -u` from your project directory and the theme will automatically update to the latest release.

---

## Contributing

Lynx is expected to evolve over time. I intend to keep adding features and making changes as required.

Feel free to get in touch with any issues or suggestions for new features you'd like to see.

- 🐛 **Bug reports & issues:** Use [GitHub Issues](https://github.com/jpanther/lynx/issues)
- 💡 **Ideas for new features:** Open a discussion on [GitHub Discussions](https://github.com/jpanther/lynx/discussions)
- 🙋‍♀️ **General questions:** Head to [GitHub Discussions](https://github.com/jpanther/lynx/discussions)

If you're able to fix a bug or implement a new feature, I welcome PRs for this purpose. Learn more in the [contributing guidelines](https://github.com/jpanther/lynx/blob/dev/CONTRIBUTING.md).
