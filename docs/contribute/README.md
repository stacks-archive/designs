# Contribute

The following is a guide to get you up to speed on the Blockstack Open Source Design Process along with guides on how to contribute, brand guide, and other resources

## Table of contents

- [Design Process](https://github.com/blockstack/designs/issues/267)
- [Blockstack Brand Guide](https://github.com/blockstack/designs/issues/247)
- [BlockstackDS (Design System) › Visit the repository](https://github.com/blockstack/design-system/issues/3)
- [Filenaming & directory structure](#filenaming--directory-structure)
- [Install & Setup Git LFS](#install--setup-git-lfs)

## Filenaming & directory structure

Each project team has a directory, seen below, and in each of the team directories are projects. Each project contains 2 standard directories for quick navigation to find files that are; 
* compositions or working files with the following filename structure
  * [filename]-[Year][Month].ext
  * Example: brand-1610.sketch
* assets files
* support and reference files

```
design/
├── example-project1/
│   ├── filename-[Year][Month].sketch
│   ├── assets/
│   └── support-files/
└── example-project2/
    ├── filename-[Year][Month].sketch
    ├── assets/
    └── support-files/

```

## Install & Setup Git LFS:

[›› More info on Git LFS](https://git-lfs.github.com/)

NOTE: Each new project [example-project1] requires tracking setup. See examples at the bottom of the tracking list below

* Files and folders to be tracked

```
*.sketch (.gitattributes)
*.psd (.gitattributes)
*.psb (.gitattributes)
*.ai (.gitattributes)
*.zip (.gitattributes)
*.indd (.gitattributes)
*.pdf (.gitattributes)
*.ppt (.gitattributes)
*.mov (.gitattributes)
*.eps (.gitattributes)
*.tif (.gitattributes)
*.mp4 (.gitattributes)
*.mp3 (.gitattributes)
*.mv4 (.gitattributes)
*.avi (.gitattributes)
*.m4v (.gitattributes)
*.aaf (.gitattributes)
*.aep (.gitattributes)
*.aet (.gitattributes)
*.indl (.gitattributes)
*.indt (.gitattributes)
*.indb (.gitattributes)
*.dmg (.gitattributes)
*.xcodeproj (.gitattributes)
*.png (.gitattributes)
*.gif (.gitattributes)
*.jpeg (.gitattributes)
*.jpg (.gitattributes)
*.svg (.gitattributes)
*.tar.gz (.gitattributes)
*.qxd (.gitattributes)
*.asc (.gitattributes)
*.csv (.gitattributes)
*.doc (.gitattributes)
*.dot (.gitattributes)
*.gdoc (.gitattributes)
*.pages (.gitattributes)
*.myo (.gitattributes)
*.myob (.gitattributes)
*.tax (.gitattributes)
*.ofx (.gitattributes)
*.qif (.gitattributes)
*.otf (.gitattributes)
*.ttf (.gitattributes)
*.woff (.gitattributes)
*.ase (.gitattributes)
*.bmp (.gitattributes)
*.icns (.gitattributes)
*.ico (.gitattributes)
*.pict (.gitattributes)
*.pdd (.gitattributes)
*.tga (.gitattributes)
*.tiff (.gitattributes)
*.cdr (.gitattributes)
*.ps (.gitattributes)
*.gslides (.gitattributes)
*.key (.gitattributes)
*.keynote (.gitattributes)
*.pez (.gitattributes)
*.pot (.gitattributes)
*.pptx (.gitattributes)
*.thmx (.gitattributes)
*.aiff (.gitattributes)
*.wav (.gitattributes)
*.m4a (.gitattributes)
*.wma (.gitattributes)
*.mp2 (.gitattributes)
*.gsm (.gitattributes)
*.aac (.gitattributes)
*.swa (.gitattributes)
*.vox (.gitattributes)
*.psf (.gitattributes)
*.band (.gitattributes)
*.logic (.gitattributes)
*.gsheet (.gitattributes)
*.xlk (.gitattributes)
*.xls (.gitattributes)
*.xlsb (.gitattributes)
*.xlsm (.gitattributes)
*.xlsx (.gitattributes)
*.xlt (.gitattributes)
*.xltm (.gitattributes)
*.xlw (.gitattributes)
*.tsv (.gitattributes)
*.asf (.gitattributes)
*.dat (.gitattributes)
*.flv (.gitattributes)
*.fla (.gitattributes)
*.mpeg (.gitattributes)
*.mpg (.gitattributes)
*.rm (.gitattributes)
*.fcp (.gitattributes)
*.ppj (.gitattributes)
*.prproj (.gitattributes)
*.imovieproj (.gitattributes)
*.bin (.gitattributes)
*.diff (.gitattributes)
*.gzip (.gitattributes)
*.rar (.gitattributes)
*.tar (.gitattributes)
*.img (.gitattributes)
*.iso (.gitattributes)
example-project1/* (.gitattributes)
example-project2/* (.gitattributes)
```