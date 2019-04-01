# A Collection of Miscellaneous Linux Configurations

Hey there! Here you can find some examples and neat ideas how to make your Linux system look and feel better!

For example, I have been experimenting for a while with Zsh, Oh-My-Zsh and Tilix and it turns out this combination is astonishing and extremely powerful. It's not only the eye candy, but the functionality that makes things faster and simpler!

At some point I will try to prettify the content with better description and some screenshots!

Cheers!

-----

## Tilix Config Backup and Restore Commands

```sh
dconf dump /com/gexperts/Tilix/ > tilix.dconf
dconf load /com/gexperts/Tilix/ < tilix.dconf
```
