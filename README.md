# minecraft-neoforge

[![Docker Build](https://github.com/dockhippie/minecraft-neoforge/actions/workflows/docker.yml/badge.svg)](https://github.com/dockhippie/minecraft-neoforge/actions/workflows/docker.yml) [![GitHub Repo](https://img.shields.io/badge/github-repo-yellowgreen)](https://github.com/dockhippie/minecraft-neoforge)

These are docker images for [Minecraft Neoforge][upstream] running on our
[Vanilla Minecraft image][parent].

## Versions

For the available versions please look at [Docker Hub][dockerhub] or
[Quay][quayio] or check the existing folders within the
[GitHub repository][github].

## Volumes

*  /var/lib/minecraft
*  /etc/minecraft/override

## Ports

*  25565
*  25575
*  8123

## Available environment variables

```console

```

## Inherited environment variables

*  [webhippie/minecraft-vanilla](https://github.com/dockhippie/minecraft-vanilla#available-environment-variables)
*  [webhippie/temurin](https://github.com/dockhippie/temurin#available-environment-variables)
*  [webhippie/ubuntu](https://github.com/dockhippie/ubuntu#available-environment-variables)

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

*  [Thomas Boerger](https://github.com/tboerger)

## License

MIT

## Copyright

```console
Copyright (c) 2023 Thomas Boerger <http://www.webhippie.de>
```

[upstream]: https://minecraft.net
[parent]: https://github.com/dockhippie/minecraft-vanilla
[dockerhub]: https://hub.docker.com/r/webhippie/minecraft-neoforge/tags
[quayio]: https://quay.io/repository/webhippie/minecraft-neoforge?tab=tags
[github]: https://github.com/dockhippie/minecraft-neoforge
