# SkyBlock Enhanced - Packwiz

This modpack is heavily based on [SkyBlock-Enhanced-Modpack](https://github.com/KdGaming0/SkyBlock-Enhanced-Modpack) and closely follows it for updates. However, instead of using Pakku for version control and building, it uses **packwiz**. The original repository is heavily bloated, taking up 2.6 GB after cloning due to `.jar` files being committed to its Git history (which isn't a fault of Pakku itself). Since I didn't want to download all that just to add a few mods, I created this clean **packwiz** repository. I also find **packwiz** easier to use than **Pakku**.

---

## Building From Source

This modpack uses **packwiz** for version control and building. Follow these steps to build it yourself:

### Prerequisites

- Install packwiz: [Installation Guide](https://packwiz.infra.link/installation/)
- Git (to clone the repository)

### Build Steps

1. **Clone or download this repository**
```bash
    git clone https://github.com/Uranite/SkyBlock-Enhanced-Packwiz.git
    cd SkyBlock-Enhanced-Packwiz
```

2. **Choose your Minecraft version**

    - Navigate to the `versions/26.1.2` folder

3. **Export the modpack**
For Modrinth (.mrpack):
```bash
    packwiz modrinth export
```
For CurseForge (.zip):
```bash
    packwiz curseforge export
```

4. **Find your build**

    - The exported modpack will be created in the current directory.

### Updating the Modpack

**To update all mods:**
```bash
packwiz update --all
```

**Learn more:** [packwiz Documentation](https://packwiz.infra.link/)

---

## Support the original SkyBlock Enhanced Project

If you want to support the original author, check it out here: [SkyBlock Enhanced on Modrinth](https://modrinth.com/modpack/skyblock-enhanced)

---

## Credits

- **Original Modpack by:** Kd_Gaming1
