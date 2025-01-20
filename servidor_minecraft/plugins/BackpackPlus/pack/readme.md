**Version:** 1.0.0

# BackpackPlus

Changing the resource pack here will not have any effect. This setup is for
the [ResourcePackManager](https://www.spigotmc.org/resources/resource-pack-manager.118574/) plugin to retrieve the
resource pack and automatically set it for players. If you do not have this plugin, any changes to the resource pack
will not be updated for backpacks. You should update the resource pack in `config.yml`.

## How to change the resource pack:

- The default resource pack is in the `pack` folder, so extract it until you have a folder with files such as `assets`,
  `pack.mcmeta`, and `pack.png`.
- You can edit them as you wish. When you're finished, add these files to a zip archive and upload it to a hosting
  service. I use: [MCPacks](https://mc-packs.net/).
- Once you have uploaded it, you should change these options in the config: `resource-pack-url` in MCPacks is the
  `Download URL`, and `resource-pack-hash` is the `SHA-1 Hash`.
- Reload the server and rejoin the server.

## Using ItemsAdder

- To ensure all backpacks work, you must add a `backpackplus` folder to the `ItemsAdder/contents` directory and create
  another folder named `resourcepack` inside it. Then, add the `assets` files from this resource pack.
- Generate the resource pack on the server using the command: `/iazip`.
