## this is my personal hacking fork. you probably want [upstream zirconium](https://github.com/zirconium-dev/zirconium).

# Zirconium
***Do you like how I dance? I've got Zirconium pants!***

## What is Zirconium?
Zirconium is an opinionated fedora-bootc image that makes use of Niri and DankMaterialShell to create a usable out of the box TWM experience.

Zirconium is built primarily for container-focused development and day-to-day usage, however gaming is still more than possible. For a fully gaming-focused experience, use Bazzite.

## How do I use this?
Currently, the best way to install Zirconium is to rebase from an existing Fedora Atomic install. We recommend [Bluefin](https://projectbluefin.io/), but it doesn't really matter.

Once you have some flavour of Fedora Atomic installed, run this command:

```
sudo bootc switch ghcr.io/zirconium-dev/zirconium:latest
```

If you also have NVIDIA GPU (GTX 16xx or RTX series), run this command instead:

```
sudo bootc switch ghcr.io/zirconium-dev/zirconium-nvidia:latest
```

If you're having issues, ask for help in our [Discord](https://discord.gg/mmgNQpxwhW). We're working on ISOs.

## Can I still customize Niri/DankMaterialShell?
Yes! We do update our dotfiles in OS updates, however you're not forced to use them. We're hoping at some point to be able to make the dotfile update process less destructive. 

## Zirconium is a stupid name. Why did you pick Zirconium?
A weird wax baby made me.

[![Tally Hall - Ruler of Everything](https://img.youtube.com/vi/I8sUC-dsW8A/0.jpg)](https://www.youtube.com/watch?v=I8sUC-dsW8A)
