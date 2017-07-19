# [Bungee Chat](https://www.spigotmc.org/resources/bungee-chat.12592/)

[![Build Status](https://gitlab.brainstonemod.com/AuraDev/BungeeChat/badges/master/build.svg)](https://gitlab.brainstonemod.com/AuraDev/BungeeChat/commits/master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/581b40c0c5ca4ca5a08c83f7076b6d63)](https://www.codacy.com/app/AuraDevelopmentTeam/BungeeChat2?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=AuraDevelopmentTeam/BungeeChat2&amp;utm_campaign=Badge_Grade)

A new way to send private, global or help messages and to do much more with chatting network wide!

## Downloads

You can download all builds from:

- SpigotMC: https://www.spigotmc.org/resources/bungee-chat.12592/
- Personal Maven: https://maven.jnc.world/dev/aura/bungeechat/BungeeChat/

## [Issue Reporting](https://github.com/AuraDevelopmentTeam/BungeeChat2/issues)

If you found a bug or even are experiencing a crash please report it so we can fix it. Please check at first if a bug report for the issue already
[exits](https://github.com/AuraDevelopmentTeam/BungeeChat2/issues). If not just create a
[new issue](https://github.com/AuraDevelopmentTeam/BungeeChat2/issues/new) and fill out the form.

Please include the following:

* Minecraft version
* Bungee Chat version
* Versions of any plugins potentially related to the issue
* Any relevant screenshots are greatly appreciated.
* For crashes:
  * Steps to reproduce
  * proxy.log.1 from the root folder of the server

*(When creating a new issue please follow the template)*

## [Feature Requests](https://github.com/AuraDevelopmentTeam/BungeeChat2/issues)

If you want a new feature added, go ahead an open a [new issue](https://github.com/AuraDevelopmentTeam/BungeeChat2/issues/new), remove the existing form and
describe your feature the best you can. The more details you provide the easier it will be implementing it.  
You can also talk to us on [Discord](https://dicord.me/bungeechat).

## Developing with our Plugin

So you want to add support or even develop an addon for our plugin then you can easily add our API to your development environment, read the
[API documentation](https://github.com/AuraDevelopmentTeam/BungeeChat2/blob/master/BungeeChatApi/README.md).

## Setting up a Workspace/Compiling from Source

* Clone:  
  Clone the repository like this: `git clone --recursive https://github.com/AuraDevelopmentTeam/BungeeChat2.git`
* IDE-Setup:  
  Run [gradle] in the repository root: `./gradlew installLombok <eclipse|idea>`
* Build:  
  Run [gradle] in the repository root: `./gradlew build`. The build will be in `build/libs`
* If obscure Gradle issues are found try running `./gradlew cleanCache clean`

## Development builds

Between each offical release there are several bleeding edge development builds, which you can also use. But be aware that they might contain unfinished
features and therefore won't work properly.

You can find the builds here: https://gitlab.brainstonemod.com/AuraDev/BungeeChat/pipelines

On the right is a download symbol, click that a dropdown will open. Select "build". Then you'll download a zip file containing all atrifacts including the
plugin jar.

## PGP Signing

All files will be signed with PGP.  
The public key to verify it can be found in `keys/publicKey.asc`. The signatures of the files will also be found in the maven.

## License

Bungee Chat 2 is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)

## Random Quote

> In software, we rarely have meaningful requirements. Even if we do, the only measure of success that matters is whether our solution solves the customer’s
> shifting idea of what their problem is.
>
> -- <cite>Jeff Atwood</cite>