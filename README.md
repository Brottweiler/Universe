# Universe

Full-stack dependencies required by the legacy `oc.tc` Minecraft plugins.

### Installation

```xml
<repository>
    <id>octc-universe</id>
    <url>https://maven.pkg.github.com/Electroid</url>
</repository>
```

```bash
mvn clean install
```

### Dependencies

Below are the equivalent dependencies included in this repository. Some like `BungeeCord` and `SportBukkit` are submodules to preserve their git history. Others are just copied over since they are not likely to significantly change.

* [`test-util`](https://github.com/OvercastNetwork/test-util)
* [`minecraft-api`](https://github.com/OvercastNetwork/minecraft-api)
* [`BungeeCord`](https://github.com/Electroid/BungeeCord)
* [`SportBukkit`](https://github.com/Electroid/SportBukkit) *(1.12.2)*
* [`sk89q-command-framework`](https://github.com/OvercastNetwork/sk89q-command-framework)
* [`BukkitSettings`](https://github.com/StratusNetwork/BukkitSettings)
* [`Channels`](https://github.com/OvercastNetwork/Channels)
* [`raven-minecraft`](https://github.com/OvercastNetwork/raven-minecraft)
* [`gson`](https://github.com/OvercastNetwork/gson)

### Extras

Included are also some other plugins that have been forked for the `oc.tc` universe.

* [`ProtocolSupport`](https://github.com/Electroid/ProtocolSupport)
* [`ViaVersion`](https://github.com/Electroid/ViaVersion)