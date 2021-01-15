#VATNZ AIRAC Changelog

- [AIRAC 2013](#airac-2013)        
    - [Revision A (Initial)](#revision-a-initial)        
    - [Revision B](#revision-b)        
    - [Revision C](#revision-c)        
    - [Revision D](#revision-d)        
    - [Revision E](#revision-e)    
- [AIRAC 2014](#airac-2014)        
    - [Revision A (Initial)](#revision-a-initial-1)    
- [AIRAC 2101](#airac-2101)        
    - [Revision A (Initial)](#revision-a-initial-2)
        - [ASMGCS](#asmgcs)
        - [Airspace Additions](#airspace-additions)
        - [Other Changes](#other-changes)
        - [Usability Changes](#usability-changes)


## AIRAC 2013

### Revision A (Initial)

Initial release of the NZ vatSys profile. 

### Revision B

No recorded changes.

### Revision C

No recorded changes.

### Revision D

No recorded changes.

### Revision E

1. Ground RADAR Views - NV, TG, RO, DN, NP, GS, AP, NR, NS and PM have all been added. Their associated ground radar has also been added. Thanks to Tom, Alek and Cam.

2. CPDLC updates - Small quality of life updates. Thanks to Zain.

3. ATIS Text-to-Speech - Now pulls clouds from the METAR string. Thanks to Zain.

4. Airspace - Fixed an issue where waypoints with the same name that were outside of NZ were being included in a flightplan. Thanks to Alex.

## AIRAC 2014

### Revision A (Initial)

1. Ownership parameters of ACU positions. All TMA positions owned by default. Thanks to Zain.

2. Initial release of [GitHub Contribution Guidelines](CONTRIBUTING.md).

## AIRAC 2101

### Revision A (Initial)

#### ASMGCS 

* Addition of NZPP, NZNE and NZAR ASMGCS views. Added the associated `RADARS.xml` and `Positions.xml` entries. Thanks to Alek and Tom.

* Separated Radar and Aerodrome Ground Views into categories within the Positions tab. Radar views are now categorised by ACU/Enroute and Aerodrome Ground Views are categorised by Class of Airspace (C/D/G). Thanks to Cam and Tom.

* Updating of NZQN ASMGCS views. Thanks to Cam and Tom.

* The following ASMGCS Taxiway, Runway and Apron labels have been added - AA, AP, AR, CH, DN, GS, HN, NE, NP, NR, NS, NV, OH, PM, PP, QN, RO, TG, WB, WN and WP. Thanks to Cam, Alek and Tom.

#### Airspace Additions

* Addition of the following Military Operating Areas (MOAs) - M106, M204, M205, M206, M207, M208, M304, M305, M504 and M507. Thanks to Tom.

* Addition of the following permanent Danger Areas - 121, 125, 130, 235, 323, 522, 621, 626, 711, 718, 719, 721, 726, 727, 820, 821, 822, 823, 827, 921, 925 and 926. Thanks to Tom.

* Addition of STAR overlays for AA, AP, AR, CH, DN, GS, HN, NE, NP, NR, NS, NV, OH, PM, PP, QN, RO, TG, WB, WN and WP. Thanks to Tom.

* Withdrawal of Miranda (RD) NDB, and replacement with waypoint MERAS. ATS Routes, and Auckland NOBAR arrivals updated. H491 and H195 have been withdrawn. 

#### Other Changes

* Addition of `<Localhost>` entry in `Profile.xml`, allowing the usage of vatSys as a FR24 viewer. Thanks to Tom and Cam.

#### Usability Changes

* Change to `README.md` to link to [CONTRIBUTING.md](CONTRIBUTING.md). Thanks to Tom.

* Updated Map file structure to for easier navigation. `_NZ/` folder deleted, with files moved to `Maps/`. ASMGCS files moved to individual folders, sorted by ICAO code. Thanks to Tom.