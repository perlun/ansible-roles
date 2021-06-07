# ansible-roles

This is a collection of Ansible roles I use to maintain my personal Linux servers.

Some of the roles were originally written as part of my day-job at [Hibox Systems](https://github.com/hiboxsystems), but I received permission to use and share them in this manner. Others are written from scratch for my personal needs.

These roles are deliberately not deployed to [Ansible Galaxy](https://galaxy.ansible.com/). They would probably need a bit more work to be "good enough" to be shared on that platform. Instead, they are distributed in this repo in a more "copy-paste" oriented fashion. Use them for inspiration when writing your own roles, use them as-is or do whatever you want with it.

Pull requests to fix obvious minor issues are welcome, but it's unlikely that any major changes will be accepted. It's probably better that you make a personal fork and maintain your changes there instead in that case.

## Roles

- [awstats](roles/awstats) - installs and configures the [AWStats](https://awstats.sourceforge.io/) web server log analyzer
- [bind](roles/bind) - installs and configures the `bind9` DNS server as well as one or more zone files.
- [nginx](roles/nginx) - installs and configures the [nginx](https://nginx.org/) web server

## License

[MIT](LICENSE)
