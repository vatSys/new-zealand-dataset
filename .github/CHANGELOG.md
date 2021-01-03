#VATNZ AIRAC Changelog

- [AIRAC 2013](#airac-2013)        
    - [Revision A (Initial)](#revision-a-initial)        
    - [Revision B](#revision-b)        
    - [Revision C](#revision-c)        
    - [Revision D](#revision-d)        
    - [Revision E](#revision-e)    
- [AIRAC 2014](#airac-2014)        
    - [Revision A (Initial)](#revision-a-initial-1)    
- [AIRAC 2101)](#airac-2101)        
    - [Revision A (Initial)](#revision-a-initial-2)

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

1. Change to `README.md` to link to [CONTRIBUTING.md](CONTRIBUTING.md). Thanks to Tom.

2. Addition of NZPP and NZNE ASMGCS views. Added the associated `RADARS.xml` and `Positions.xml` entries. Thanks to Alek and Tom.

3. Addition of `<Localhost>` entry in `Profile.xml`, allowing the usage of vatSys as a FR24 viewer. Thanks to Tom and Cam.

4. Separated Radar and Aerodrome Ground Views into categories. Radar views are now categorised by ACU/Enroute and Aerodrome Ground Views are categorised by Class of Airspace (C/D/G). Thanks to Cam and Tom

5. NZQN ASMGCS Files reworked. Thanks to Cam and Tom.