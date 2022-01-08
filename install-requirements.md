# Install Requirements

* Download the latest release from [https://github.com/TEdit/Terraria-Map-Editor/releases/latest](https://github.com/TEdit/Terraria-Map-Editor/releases/latest)
* Scroll to the bottom, and ensure you download the TEdit(version).zip File
* ![](<.gitbook/assets/image (35) (1).png>)
* Unzip the download to an _empty_ folder **with write access**, such as `c:\games\TEdit`.
* ![](<.gitbook/assets/image (35).png>)
* NOTE: you may need to delete OLD versions of files from this folder first.
* Launch the exe file
* ![](<.gitbook/assets/image (34).png>)

## REQUIRED

{% hint style="danger" %}
These are requirements these, if you are having issues please uninstall/reinstall the following dependencies.
{% endhint %}

* [Latest DotNet Framework](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net48-web-installer)
* [DirectX 11](https://support.microsoft.com/en-us/kb/179113)
* Update your Graphics Driver to latest release (not beta) version
* **Only Windows 10 x64** has been tested, previous versions (XP, 7, 8) are _**NOT guaranteed**_ to work and support will be limited.

## For Sprite Viewing

* Terraria must be installed or the data files must be available, normally
  * 64bit: `Program Files (x86)\Steam\steamapps\common\Terraria\content`
  * 32bit: `Program Files\Steam\steamapps\common\Terraria\content`
* Steam and Gog versions of Terraria normally work. However, you might be able to get other types to work with the steps below.
* If you don't have Terraria installed on the PC you are using there will be no sprite visualization, but the application should still work if you meet the other requirements.
*   If you don't have Terraria installed but have a copy of Terraria/Content e.g. shared network drive, virtual machine, USB drive, etc., you can uncomment and edit `<AltC>` in settings.xml to point to your custom Terraria/Content location.

    NOTE: Remove the `<!--` and `-->` to uncomment the line

![](<.gitbook/assets/altc (2) (2).png>)

![](<.gitbook/assets/gog (2).png>)

## Known Limitations

* NOT compatible with any mod files or TConfig modified worlds
* ONLY supports textures with a Steam copy of Terraria installed
  * If you don't have Terraria installed but have access to Terraria/Content (e.g. shared network drive, USB), you can point to it by uncommenting and editing \<AltC> in settings.xml

## Note

* Some older integrated graphics chipsets, old netbooks/laptops, may not work! TEdit may or may not work with these older integrated graphics chipsets.
* nVidia 770 are known to have issues with certain driver versions, please update and reinstall DirectX/.Net
* If you have the option of using Integrated Graphics or GPU (nVidia/ATI) and are having issues, try switching this setting.
