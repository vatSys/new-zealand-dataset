# VATNZ AIRAC Changelog

### 2020 Releases
- [AIRAC 2013](#airac-2013)   
- [AIRAC 2014](#airac-2014)

### 2021 Releases
- [AIRAC 2101](#airac-2101)
- [AIRAC 2102](#airac-2102)
- [AIRAC 2103](#airac-2103)
- [AIRAC 2104](#airac-2104)
- [AIRAC 2105](#airac-2105)
- [AIRAC 2106](#airac-2106)
- [AIRAC 2107](#airac-2107)


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

* Addition of the following Military Operating Areas (MOAs) - M106, M204, M205, M206, M207, M208, M304, M305, M504 and M507.

* Addition of the following permanent Danger Areas - 121, 125, 130, 235, 323, 522, 621, 626, 711, 718, 719, 721, 726, 727, 820, 821, 822, 823, 827, 921, 925 and 926.

* Addition of STAR overlays for AA, AP, AR, CH, DN, GS, HN, NE, NP, NR, NS, NV, OH, PM, PP, QN, RO, TG, WB, WN and WP.

* Withdrawal of Miranda (RD) NDB, and replacement with waypoint MERAS. ATS Routes, and Auckland NOBAR arrivals updated. H491 and H195 have been withdrawn.

#### Other Changes

* Addition of `<Localhost>` entry in `Profile.xml`, allowing the usage of vatSys as a FR24 viewer. Thanks to Tom and Cam.

* Bug fixed where activation of flight plans do not show up as activated on the APP / ENR controller's scope. Thanks to Zain.

#### Usability Changes

* Change to `README.md` to link to [CONTRIBUTING.md](CONTRIBUTING.md). Thanks to Tom.

* Updated Map file structure to for easier navigation. `_NZ/` folder deleted, with files moved to `Maps/`. ASMGCS files moved to individual folders, sorted by ICAO code. Thanks to Tom.

## AIRAC 2102

### Revision A (Initial)

* Added NZMF in `AIRPORTS.xml`

* Changed the file structure for our Maps, making it more logical and better organised. All referenced links have been updated.

* Made the coastline a little bit darker, in order to better distinguish between the coastline and airspace boundaries.

* Changed the colours of VORs and NDBs. The symbols are now also accurate.

* Changed what Map layers are viewable by default in both Enroute and ACU views. Views should no longer be as cluttered.

### Revision B

* Dataset did not update due to an error that I made. This should fix it.

### Revision C

* VatSys build 0.1.7732.21010 caused some arrival list, and button colours to go out of kilter. Fixed.

### Revision D

* vatSys build 0.1.7735.27676 adds support for custom button select, window border colours and tick styles. Changes have been made so this fals in like with the NZ Dataset.

## AIRAC 2103

### Revision A (Initial)

* Change of Queenstown Ground and Delivery frequencies.

* Addition of various ADS-B radar sites, to bring our coverage further into line with the real-world system.

## AIRAC 2104

### Revision A (Initial)

* **Queenstown** - REDOL2A renamed to the REDOL1B, along with the addition of the SUNGU transition;
* **Queenstown** - Addition of the DOVMA1A departure, RWY 05. 

#### Major Feature Update #1

* All aerodromes in the NZ Domestic FIR have been added.
* All aerodrome procedurs have been added. This includes SIDs, STARs, RNP and GNSS approaches.
* All ATS Routes have been added.
* All VRPs have been added, alongwith VFR arrivals and departures.

### Revision B

Hot fixes for the Anzac Day event.

* **Auckland** - Waypoint BATOS added to the OSRAP1P/MADEP SID.
* **Queenstown** - ANPOV3D renamed to the ANPOV4D.

## AIRAC 2105

### Revision A (Initial)

* The following aerodrome procedures have been added: Glentanner (NZGT), Alexandra (NZLX), Manapouri/Te Anau (NZMO), Takaka (NZTK) and Whitianga (NZWT). As a part of this, some procedural fixes have been added.
  
* Addition of Paraparaumu and Milford FIS as positions. As defined in the Airspace section of the VATNZ website, these are Events Only positions.

* Removal of Dunedin Ground and Delivery positions. 

* Palmerston and Ohakea Ground positions have been added.

* Addition of updated `Performance.xml`, which includes aircraft type information (speeds, climb and descent rates). 

## AIRAC 2106

### Revision A (Initial)

**ANR database updated, with the following changes**:
 * WPT `VAMSU` replaced with WPT `BUGNO`. New Plymouth procedures have been changed (see below).
 * Additon of waypoints `OLGOP`, `IGDAR`, `EMSED`,  `URKEL`, `ELDIB`. 
 * Airways `KQ427`, `H191` and `Y273` amended.
 * Minor changes to controlled airspace bounds.
 * New Whanganui VRPs have been added.

**New Plymouth (NZNP) Changes**
Mainly changes to bring the procedure notation in line with convention, and to reflect the replacement of WPT `VAMSU` with `BUGNO`.

 * **VISAD 3A** replaces VISAD 2A.
 * **BUGNO 1B** replaces VAMSU 2B.
 * **SAVLO 3P** replaces SAVLO 2P.
 * **GUSUR 2Q** replaces GUSUR 1Q.
 * **LATIG 2Q** replaces LATIG 1G.

**A-SMGCS (Ground Radar views)**
ASMGCS files are being progressively updated to bring them into naming standardizations, to allow for the automatic converting of them between vatSys and EuroScope. We're also taking this time to add additional features and details, including highly detailed terminals and grass runways.

  * Woodbourne view redesigned. Implementation of grass runways. 
  * Christchurch view redesigned. Implementation of grass runway.
  * Auckland view redesigned.
  * Wellington view redesigned.

Major domestic aerodromes are next on the working list.


## AIRAC 2107

### Revision A (Initial)

**ANR database updated, with the following changes**:
  * Minor updates to Airways routing.
  * Minor CTA/Navaid co-ordinate changes.

* Fixed a minor error where the Auckland RADAR SIDs were assigned to the incorrect runway.. oops.
* Added a QNH zone map. The airfield in the brackets denotes the reference aerodrome for that QNH region.

### Rush Revision B (Issued 19 JUL)

  * Some waypoints within `Airways.xml` were duplicated from the NZ ANR export, causing a vatSys error. This RR removes the duplicate waypoints.
  * Some Palmerston North procedure notation changed - `GUTNU 3R`, `GUTNU 3T`.
