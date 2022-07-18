# btrfdeck - (butter-f-deck)
Improve your Steam Deck with eight simple steps! **This is potentially unsafe and a little buggy. Don't do this unless you know what you are doing! I will change the text in this notice when I am confident in the guide for non-techy people :-)**

The instructions and files on this page are designed to help you format microSD cards for your Steam Deck with [BTRFS](https://btrfs.wiki.kernel.org/index.php/Main_Page). This can lead to [tremendous storage space savings](#but-why) and even [faster loading performance](#but-why).

This process involves changing two files in the protected SteamOS partition, which will allow you to format your card more easily and then enable the Deck to automatically mount the card with compression-on-write on insert!

This repo is identical to Trevo525's, but removes the "compress-force" tag in favor of the standard "compress". This means that files will only be compressed if space would be saved, which may reduce redundant CPU usage.
