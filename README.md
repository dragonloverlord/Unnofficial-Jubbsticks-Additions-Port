# **The Unofficial Jubbsticks Additions Port**
An unofficial community preservation port of Jubbsticks Additions for Animal Crossing: New Horizons (ACNH), created to keep this wonderful mod playable on modern updates

---

### ⚠️ **UNOFFICIAL BETA RELEASE**  

This is a work-in-progress testing build, not an official release from Jubbsticks. It is based on collaborative work from August 2026 before IRL responsibilities pulled Jubbsticks away from the project. While it has been tested and is largely playable, expect rough edges. Back up your save data before installing.


---
# **Important Rules & Expectations**

### **Please read these before downloading, reporting issues, or contributing**:
* **Do not contact Jubbsticks for support**: They are not maintaining this build and will not support saves used with it if they return for an official update. Direct all feedback to this repository. Additionally, If at any point Jubbsticks does return and a decision regarding an official release is made then I'll definitely post an update here saying as much as well explaining what it means for this repo / version.
* **Do not redistribute as official or re-upload**: Keep this clearly labeled as an Unofficial Beta. Do not upload it to GameBanana, Nexus Mods, or other modding sites without explicit permission from Jubbsticks. As doing so could cause unnecessary confusion for users and would likely lead to a bunch of fragmented half functional unsupported versions floating around the internet. 
* **No AI-generated spam**: Please do not submit AI-generated bug reports, code pull requests, or automated patches. As a solo maintainer with limited free time I can't review or merge AI-generated submissions. Additionally, even if I did have the free time to vet AI submissions I'd Still need Jubbsticks approval regarding the usage of AI in the development of the mod before I'd consider allowing it. 
* **Offline play only**: Playing modded ACNH online violates Nintendo's terms, risks account/console bans, and is completely untested in this beta. That said emulators with LDN functionality may work, but bug are to be expected. Additionally, the configuration of said emulator is the users responsibility and compatibility can't be guaranteed.
* **Zero tolerance for piracy**: Only legitimate, user-dumped copies of the game are supported. Pirated ROMs, repacks, and bad dumps can cause crashes and contain bugs that simply don't exist in a proper dump / copy of the game. No game files, keys, or firmware are hosted here, and any discussion or requests involving piracy will be removed immediately to protect the project from DMCA takedowns.
* **Be respectful**: Keep discussions family-friendly and treat everyone with basic decency.

# **Installing**
There are two supported ways of installing the mod and which one you use will likely come down to your setup.  

### Atmosphere (Nintendo Switch & Accepted By Most Emulators)
* Download "Atmosphere" version from [Releases](https://github.com/dragonloverlord/Unnofficial-Jubbsticks-Additions-Port/releases).
* Extract the atmosphere folder onto the root of your SD card overwriting as needed.
* If any files conflict with other mods please consult the "Merging & File Info" section below.

### Emulator Mod Manager (Preferred By Some Emulators)
* Download "Emulator" version from [Releases](https://github.com/dragonloverlord/Unnofficial-Jubbsticks-Additions-Port/releases).
* Extract "Unofficial Jubbsticks Additions Port" folder to your emulators mods folder.
* Enable the mod in your emulators settings / mod settings.
* If any files conflict with other mods please consult the "Merging & File Info" section below.

### Merging & File Info
* If you have conflicting files (from other mods) while merging, I would suggest reviewing the list of [common-conflicts](https://github.com/dragonloverlord/Unnofficial-Jubbsticks-Additions-Port/blob/main/FileInfo.md) to understand what each of these files does. These tend to be important for the mod's functionality, but if you prefer the function provided by another mod you may pick and choose which files to include.
* Make sure to back up of your saves and make a backup of any mod you plan to before you delete / overwrite anything
* If using an emulator then you may have to adjust the load order of your mods or manually remove any conflicting files from the mod you want to be overwritten.
* **IMPORTANT** RSTB Patch Info (ResourceSizeTable.srsizetable): The mod comes with an RSTB file (in the System folder) that is required to load it's model / texture changes. If you want to use any mod that adds or changes textures / models then you'll have to generate a new ResourceSizeTable.srsizetable to avoid crashing. This can be done with Heavens Tool amongst other tools.

---
# **Differences & Feature Changes**
Obviously some stuff had to change to get things working again. Thankfully though it's required much less in terms of breaking changes than expected. So I'll simply keep a list of the confirmed / expected differences from the original here for now.

### Added
* **Stackable Items**: Fish, Insects, and Dive fish all stack now as do other things when possible like garbage (boots, tires. etc.) & clams.

### Changed
* **Bait Bulk Crafting**: Technically ACNH now supports bulk crafting natively, but I did attempt to port the changes over anyway.
* **Bait Bulk Crafting Nook Miles Achievement**: Due to bulk crafting being a standard feature now there's a good chance this Nook Miles Achievement will simply be removed as it's borderline irrelevant / serves no purpose anymore.
* **Hotel DIY Deliveries**: Mod Added Tool & Balloon DIY recipes have been manually flagged as being invalid for the new Hotel DIY Deliveries feature so they don't show up as requests since they use the rare and hard to get gemstones from the mod and if enabled show up way too often as a request and do so at to high a quantity to be reasonably completed.
* **Tool Durability**: All tools are unbreakable now. In the future I may consider making a version with only the gold & gem tools unbreakable but for debugging / development simply making them unbreakable was the easiest option for the time being.
* **Stack limits**: Item stack limits have been increased to 254 AKA the hard limit (It's a 1 byte field and 255 / 0xFF is reserved so using it causes stacks to vanish or return to 1 randomly).

### Removed
* **2 Bananas per Tree**: Relied on an external third-party exeFS patch that is no longer available.
* **Non-English Translations**: Omitted for now because I only speak English and manually porting localization files is too time-consuming (one of the most tedious parts of porting this mod actually). Community translation contributions are welcome down the line.

---
