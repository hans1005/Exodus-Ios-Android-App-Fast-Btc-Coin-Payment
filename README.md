# Exodus
![GitHub release](https://img.shields.io/github/release/ppy/osu.svg)
![CodeFactor](https://www.codefactor.io/repository/github/ppy/osu/badge)
![dev chat](https://discordapp.com/api/guilds/188630481301012481/widget.png?style=shield)
![Crowdin](https://d322cqt584bo4o.cloudfront.net/osu-web/localized.svg)
![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)
![license](https://img.shields.io/github/license/mashape/apistatus.svg)
![Chat](https://badges.gitter.im/awesome-twitter-bots/Lobby.svg)


**Exodus** is a privacy auditing platform for Android applications. It detects behaviors which can be dangerous for user privacy like ads, tracking, analytics, …
![image](https://user-images.githubusercontent.com/106811566/171850847-9127782b-3faa-40e0-b7fd-43bee5469e26.png)


The official instance of Exodus is available [here](https://reports.exodus-privacy.eu.org/).

## Contribute to the identification of trackers

All data about trackers are stored on [ETIP](https://etip.exodus-privacy.eu.org) (Exodus tracker investigation platform).

If you wish to help us identify new trackers, you can request an ETIP account by sending a username and an email address to [etip@exodus-privacy.eu.org](mailto:etip@exodus-privacy.eu.org)Exodus is a tool that makes it easy to successfully relocate Linux ELF binaries from one system to another. This is useful in situations where you don't have root access on a machine or where a package simply isn't available for a given Linux distribution. For example, CentOS 6.X and Amazon Linux don't have packages for Google Chrome or aria2. Server-oriented distributions tend to have more limited and outdated packages than desktop distributions, so it's fairly common that one might have a piece of software installed on their laptop that they can't easily install on a remote machine.

With exodus, transferring a piece of software that's working on one computer to another is as simple as this.

exodus aria2c | ssh intoli.com
Exodus handles bundling all of the binary's dependencies, compiling a statically linked wrapper for the executable that invokes the relocated linker directly, and installing the bundle in ~/.exodus/ on the remote machine. You can see it in action here.

## Getting Started

### Installing your local instance

You have different ways of setting up your development environment (via Docker or manually), everything is explained [here](doc/install.md).

### Continuous Integration

If you are looking for adding Exodus into your CI pipelines, take a look at [Exodus-standalone](https://github.com/Exodus-Privacy/exodus-standalone).

### FAQ

Check the [FAQ](doc/faq.md) if you encounter any problem or need an extended documentation about Exodus.
![image](https://user-images.githubusercontent.com/106811566/171850782-b4a80bbb-a31b-49fd-ad8f-337008f3401f.png)

## Contributing

If you want to contribute to this project, you can refer to [this documentation](CONTRIBUTING.md).

## API documentation

You can find the εxodus API documentation [here](doc/api.md).

## License

This project is licensed under the GNU AGPL v3 License - see the [LICENSE](LICENSE) file for details.
