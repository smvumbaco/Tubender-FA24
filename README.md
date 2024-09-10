# <PROJECT NAME>
<ADD BLURB ABOUT PROJECT>

## Directory Structure:
```
.
|
|───production  # contains files needed for final prototype
|   |
|   |───eCAD    # contains the KiCAD project
|   └───src     # contains the code needed for deployment
|
|───testing     # contains files relevant to testing components
|
└───README.md   # this file!
```

## Preferred Tools
- KiCAD for PCB development
- Visual Studio Code / PlatformIO for code development
- Git CLI / GitHub Desktop for managing Git

## Branches
> To isolate conflicts for schematics and code, we use two branches to actually develop off of depending on discipline
- `develop/ecad` is for schematic development, please create PR's into this branch for schematics and operate in this branch for layout
- `develop/src` is for code development, please create PR's into this branch for features

## References
- Schematics + Components (WIP)

## Practice Good Git Hygiene!
1. Only commit files you intended to change
2. Create branches for each feature, and larger branches for each development effort (i.e. ```develop/*```)
3. Check your branch before starting work
4. Pull frequently to avoid conflicts
5. Make Pull Requests when you are ready to merge into a larger branch

## Git Resources

* [Setting up Git](https://fanatical-colossus-434.notion.site/Git-Installation-and-Setup-d07b7d1ab5544424876f9fd3b4a0b312)
* [Intro to Git Crash Course](https://fanatical-colossus-434.notion.site/Crash-Course-Intro-to-Git-809641611da9478b8f9cca8fd97e49fe)
