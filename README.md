## EmiliaMC
EmiliaMC is currently **under heavy development** and contributions are welcome!

Introduction
---
> EmiliaMC is a powerful server software from the 'new dimension', formerly known as Torch.

As a [Paper](https://github.com/PaperMC/Paper) fork, it should support almost all plugins that work on [Spigot](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/spigot/browse).

Our project has a few key goals:

* **Open Access** - Make more game mechanics configurable.
* **Bedrock** - Make the server more safe and stable. 
* **Fast** - Simplify the logic and implement multi-threaded computing.

*Issues and Pull Requests will be labeled accordingly*

Get EmiliaMC
---
### Download
#### Recommended
+ [**Circle CI**](https://circleci.com/gh/Emilia1012/EmiliaMC/tree/ver/master) - Checkout the 'Artifacts' tab of the latest build *Login required*

### Build
#### Requirements
* Java (JDK) 8 or above
* Maven

#### Compile
```sh
./scripts/inst.sh --setup --fast
```

**Notes**
* You must use `--setup` at least once to deploy necessary dependencies otherwise some imports cannot be organized.
* For non-modified projects, it is recommended to add the `--fast` option to skip any tests.
* If your machine has insufficient memory, you may want to add the `--remote` option to avoid decompiling locally.

Demo Servers
---

* [LoyaltyMC](https://minecraft-mp.com/server-s212077)

Contributing
---
* You can checkout the `src` folder to see more. Please follow the patch style to do any change, so we are able to update between different Minecraft versions.
* Add your name to the [LICENSE](https://github.com/Akarin-project/Akarin/blob/master/LICENSE.md) if you want to publish your code under the [MIT License](https://github.com/Akarin-project/Akarin/blob/master/licenses/MIT.md).
* If you want to join the [Akarin-project](https://github.com/Akarin-project) team, you can [send](mailto://kira@kira.moe) us an email with your experience and necessary information.