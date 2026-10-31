# Unraid templates by smiei

Docker templates for [Unraid](https://unraid.net/) Community Applications.

| App | Template | Image |
| --- | --- | --- |
| [Lockstep](https://github.com/smiei/lockstep) - SoulLink & Nuzlocke tracker | [`templates/lockstep.xml`](templates/lockstep.xml) | `ghcr.io/smiei/lockstep` |

## Install

Search for **Lockstep** in the **Apps** tab of Unraid.

Until it is listed there, add the template by hand (Unraid 6.10 and later no longer take template repository URLs): open a terminal on the server (**>_** in the top bar) and run

```sh
wget -O /boot/config/plugins/dockerMan/templates-user/my-lockstep.xml \
  https://raw.githubusercontent.com/smiei/unraid-templates/main/templates/lockstep.xml
```

Then **Docker → Add Container → Template** and pick **lockstep** under *User templates*.

The app's own documentation covers volumes, variables and updates: [self-hosting guide](https://github.com/smiei/lockstep/blob/master/docs/self-hosting.md).

## Support

Questions and bug reports go to the app's [issue tracker](https://github.com/smiei/lockstep/issues).

## License

The templates in this repository are released under the [MIT License](LICENSE). The apps they install have their own licenses.
