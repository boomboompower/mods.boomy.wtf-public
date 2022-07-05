# mods.boomy.wtf public
A repository containing all mods listed on mods.boomy.wtf

If you would like to add your **Github** mod to the website, please either create a PR or make an issue. The format for a mod is as follows

```jsonc
  {
    "author": "Username",               // The github username/org which the repo is stored under
    "repository": "Repository",         // The github repository which the repo is stored under
    "description": "My description",    // A small description of the mod, 
    "description_key": "EXP",           // 2-5 letter unique key of your mod 
    "release_sorting": false            // Please see below for more info
  },
```

### Author [ `author` ]
This is your Github username or the organization which the repository is hosted under. E.g `boomboompower` 

### Repository [ `repository` ]
This is the name of the repository as seen on the repo. E.g `mods.boomy.wtf-public`

### Description [ `description` ]
A short description of your mod for a user to see. Short and concise is usually a good idea.

I generally like to:
* Provide what gamemode the mod is for, or where it can be used
* Explain what it does in as few words as possible
* Use very simple terminology

### Description Key [ `description_key` ] 
Just a unique identifier for your mod, should be 2-5 letters and _unique_

This is mostly used for translations, so it is optional.

### Release Sorting [ `release_sorting` ]
If this is true, the website tries to use [Semantic Versioning](https://semver.org/) to sort releases. 

This tag is optional, and if ommitted the default Github sorting will be used.
