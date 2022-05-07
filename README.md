# EF2022 Repo 

el_wire     - Kicad 5 Project Files for Totem El Wire driver  
TotemDuck   - code for custom Mama duck role using ClusterDuck Protocol

## Getting started with ClusterDuck Radios

https://github.com/Call-for-Code/ClusterDuck-Protocol

## Getting started with the schematics
    git clone --branch kicad-5 https://github.com/kitspace/kicad_footprints
    cd kicad_footprints && ./init

### Registering with KiCAD

You can add these libraries manually through the KiCAD GUI of course.
You could also use `generate_table` to generate an fp-lib-table, the file KiCAD uses as a footprint registry, with all the footprints from this repository.
You can use this to replace your existing fp-lib-table.
You will need to restart KiCAD for this change to take effect.

#### Linux

    cp ~/.config/kicad/fp-lib-table ~/.config/kicad/fp-lib-table.backup
    ./generate_table ~/.config/kicad/fp-lib-table

#### Mac OS

    cp ~/Library/Preferences/kicad/fp-lib-table ~/Library/Preferences/kicad/fp-lib-table.backup
    ./generate_table ~/Library/Preferences/kicad/fp-lib-table

#### Windows (using [git-bash](https://git-scm.com/download))

    cp ~/AppData/Roaming/kicad/fp-lib-table ~/AppData/Roaming/kicad/fp-lib-table.backup
    ./generate_table ~/AppData/Roaming/kicad/fp-lib-table
