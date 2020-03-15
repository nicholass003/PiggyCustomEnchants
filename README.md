# PiggyCustomEnchants [![Poggit-CI](https://poggit.pmmp.io/ci.badge/DaPigGuy/PiggyCustomEnchants/PiggyCustomEnchants/master)](https://poggit.pmmp.io/ci/DaPigGuy/PiggyCustomEnchants) 

PiggyCustomEnchants is an open-sourced custom enchants plugin for [PocketMine-MP](https://github.com/pmmp/PocketMine-MP) featuring over 90 custom enchantments.

<!-- If one question constantly persists, add the Q/A in here. -->
## FAQ
**Q:** How do I create/use an enchanted book? </br>
**A:** If you want to create an enchanted book, use the /ce enchant command on a normal book. Afterwards, you place the item you want to enchant on top of the enchanted book. It will then enchant your item.

**Q:** `ErrorException: "Invalid argument supplied for foreach()" (EXCEPTION) in "plugins/PiggyCustomEnchants.phar/src/DaPigGuy/PiggyCustomEnchants/PiggyCustomEnchants" at line 54` </br>
**A:** This is due to an outdated configuration from Version 1.0.0. You should delete your old configuration to allow PiggyCE to re-generate a new configuration.

## Commands
| Command | Description | Permissions | Aliases |
| --- | --- | --- | --- |
| /customenchant | Main command for PiggyCustomEnchants | `piggycustomenchants.command.ce` |  `/ce` |
| /customenchant about | Shows version and author information | `piggycustomenchants.command.ce.about` | `/ce about` |
| /customenchant enchant | Command to enchant an item with custom enchants | `piggycustomenchants.command.ce.enchant` | `/ce enchant` |
| /customenchant help | Lists all PiggyCustomEnchant commands | `piggycustomenchants.command.ce.help` | `/ce help` |
| /customenchant info | Gives information on a custom enchant | `piggycustomenchants.command.ce.info` | `/ce info` |
| /customenchant list | Lists all PiggyCustomEnchants enchants | `piggycustomenchants.command.ce.list` | `/ce list` |
| /customenchant nbt | Outputs the NBT of the held item | `piggycustomenchants.command.ce.nbt` | `/ce nbt` |
| /customenchant remove | Removes a custom enchant from the held item | `piggycustomenchants.command.ce.remove` | `/ce remove` |
=
## Permissions
| Permissions | Description | Default |
| --- | --- | --- |
| `piggycustomenchants` | Allows usage of all PiggyCustomEnchants features | `op` |
| `piggycustomenchants.command` | Allow usage of all PiggyCustomEnchants commands | `op` |
| `piggycustomenchants.command.ce` | Allow usage of the /customenchant command | `op` |
| `piggycustomenchants.command.ce.about` | Allow usage of the /customenchant about subcommand | `true` |
| `piggycustomenchants.command.ce.enchant` | Allow usage of the /customenchant enchant subcommand | `op` |
| `piggycustomenchants.command.ce.help` | Allow usage of the /customenchant help subcommand | `true` |
| `piggycustomenchants.command.ce.info` | Allow usage of the /customenchant info subcommand | `true` |
| `piggycustomenchants.command.ce.list` | Allow usage of the /customenchant list subcommand | `true` |
| `piggycustomenchants.command.ce.nbt` | Allow usage of the /customenchant nbt subcommand | `true` |
| `piggycustomenchants.command.ce.remove` | Allow usage of the /customenchant remove subcommand | `op` |
| `piggycustomenchants.overridecheck` | Allow overriding of custom enchant level limit and item restriction | `false` |

## Issue Reporting
* If you experience an unexpected non-crash behavior with PiggyCustomEnchants, click [here](https://github.com/DaPigGuy/PiggyCustomEnchants/issues/new?assignees=DaPigGuy&labels=bug&template=bug_report.md&title=).
* If you experience a crash in PiggyCustomEnchants, click [here](https://github.com/DaPigGuy/PiggyCustomEnchants/issues/new?assignees=DaPigGuy&labels=bug&template=crash.md&title=).
* If you would like to suggest a feature to be added to PiggyCustomEnchants, click [here](https://github.com/DaPigGuy/PiggyCustomEnchants/issues/new?assignees=DaPigGuy&labels=suggestion&template=suggestion.md&title=).
* If you require support, please join our discord server [here](https://discord.gg/qmnDsSD).
* Do not file any issues related to outdated API version; we will resolve such issues as soon as possible.
* We do not support any spoons of PocketMine-MP. Anything to do with spoons (Issues or PRs) will be ignored.
  * This includes plugins that modify PocketMine-MP's behavior directly, such as TeaSpoon.

## Information
* We do not support any spoons. Anything to do with spoons (Issues or PRs) will be ignored.
* We are using the following virions: [Commando](https://github.com/CortexPE/Commando) and [libFormAPI](https://github.com/jojoe77777/FormAPI).
    * **You MUST use the pre-compiled phar from [Poggit-CI](https://poggit.pmmp.io/ci/DaPigGuy/PiggyAuctions/~) instead of GitHub.**
    * If you wish to run it via source, check out [DEVirion](https://github.com/poggit/devirion).
* Plugin setup/configuration information & API Documentation available at [PiggyDocs](https://piggydocs.aericio.net/PiggyCustomEnchants.html).
* You can find a list of custom enchants at [PiggyDocs](https://piggydocs.aericio.net/PiggyCustomEnchants.html).
* Check out our [Discord Server](https://discord.gg/qmnDsSD) for additional plugin support.

## License
```
   Copyright 2017-2020 DaPigGuy

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

```