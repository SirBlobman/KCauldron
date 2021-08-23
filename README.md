# KCauldron
A continuation of Cauldron.

## Compilation Instructions
I created a modified version of ForgeGradle 1.2-SNAPSHOT that is used to compile this project.
The instructions below should work for most setups. Make sure to compile this with JDK 8.

1) Checkout this project.
2) Init Submodules: `git submodule update --init --recursive`
3) Setup the workspace: `gradlew setupCauldron`
4) Build ZIP: `gradlew packageBundle`

Note: all binaries will be in the `distributions` folder.

## Contributing
I am not accepting any PRs to this restoration.
The project will remain as-is unless there is a need to repair something.

## Credits
* [MCP](http://mcp.ocean-labs.de) - permission to use data to make Cauldron.
* [Forge](http://www.minecraftforge.net) - mod support.
* [CraftBukkit](http://bukkit.org) - plugin support.
* [Spigot](http://www.spigotmc.org) - performance optimizations.
* [djoveryde/KCauldron](/djoveryde/KCauldron) - The repository that allowed me to make this restoration.
