OpenBlox is a game engine that is simple enough to be used by beginners to programming yet powerful enough to fit the needs of more serious developers. It provides a Lua API to enable developers to create games easily and with few restrictions. This is the official website of the OpenBlox project. The servers providing the infrastructure and services used by the OpenBlox project, collectively called [OBNet]({{< relref "obnet.md" >}}).

It is important to note that the “Open” in “OpenBlox” does not refer to “open source” but rather to the potential of the OpenBlox engine. Our goal is to provide a [free (libre)](https://www.gnu.org/philosophy/free-sw.html) game engine, not to promote “open source” software. The OpenBlox game engine itself is under the [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.html), version&nbsp;3 or later. The reference client and server implementations, as well as the studio software, are licensed under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html), version&nbsp;3 or later.

OpenBlox needs your help! If you are a programmer and would like to contribute, please see [our instructions]({{< relref "contributing.md#development" >}}) to get the source code and submit merge requests or send patches.

## Goals

The aim of the OpenBlox project is to create a fully free game engine that provides the base components to create simple games in a 3D virtual space. We want the game engine to implement physics and rendering and to offer objects that implement characters, physical objects, graphical user interfaces, terrain, particle effects, vehicles and to provide APIs and objects to change the game lighting, send network requests, play sounds, get mouse and keyboard input and much more.

At the foundation of our goals are a few guiding principles:

* You should not have to implement complicated stuff like rendering, physics, and multiplayer networking.
* Instead, the game engine should provide you with components you can use to create games.
* The components should be general enough not to restrict the breadth of games that you can create.
* The whole engine should be fully free and available on all the major operating systems (GNU/Linux, Microsoft Windows, macOS, Android and iOS).
* It should be easy to learn.

## Obtaining

We do not currently provide binaries for OpenBlox. You can download the source code from [git.openblox.org](https://git.openblox.org) and build it. You will first need to install the dependencies.

## Game development

OpenBlox uses the Lua programming language. It provides a scripting API similar to that of the proprietary Roblox game engine and attempts to remain at least partially compatible with that engine.

### Documentation

OpenBlox uses Doxygen to document the C++ API. The documentation for the latest build is available on [doxygen.openblox.org](https://doxygen.openblox.org).

Documentation for the Lua API is located on [a separate site](https://docs.openblox.org).

### Support

We do not provide professional support for OpenBlox. However, if you want to get help, you can connect to the freenode IRC network and [join the channel #OpenBlox](ircs://chat.freenode.net/OpenBlox).

## Donating

The OpenBlox project currently accepts donations by PayPal. You can find our [current addresses](/donate.asc) signed by the project leader. While monetary contributions help keep our servers running, there are other ways to help the project. We’re always looking for new contributors, to keep OpenBlox going strong.
