# Clue Hunter Finder Plugin

This plugin helps you find the different clue hunter items distributed over RuneScape.

To start looking for an item you can type `::find <item descriptor>` in the gamechat. If the item descriptor matches any
of the descriptors in the table below, a hint arrow will appear on your minimap pointing you in the right direction. To
cancel your search, you can type `::find cancel`.

Supported item descriptors are:

|  Item | Descriptor  |
|---|---|
| Clue hunter boots  |  chboots |
| Clue hunter gloves  |  chgloves |
| Clue hunter cloak |  chcloak |
| Clue hunter garb |  chgarb |
|  Clue hunter trousers | chtrousers |

Example command: `::find chboots`

### Limitations

The item finder detects if the item you are trying to find is already equipped/in your inventory. It does not check if
the item in question is in your bank. In case the item finder detects you already have the item, the command will be
ignored.
