---
name: "[Tracking Issue] NZZC Cycle "
about: To be used as a tracking issue for scheduled NZZC data releases.
title: "[Tracking Issue] NZZC Cycle 2xxx"
labels: ''
assignees: ''

---

### Preparation:
- [ ] Prepare ANR data and commit to #ais-data-manager
- [ ] Sort through AIP Bulletin and create tickets for each AD, noting the specific change.
- [ ] Assess necessary changes to non-procedural data, such as Control Positions, frequencies, etc - raising project tickets where necessary.
- [ ] Assess changes to Standard Route Data - raising project tickets where necessary.
- [ ] Assess necessary changes to SOPs. Open a project ticket with a linked issue in the SOPs repository. Move to "Awaiting SOPs Change"

### Data Changes
- [ ] Duplicate procedure changes in SFG, as per the relevant project ticket.
- [ ] Implement any other changes required as a part of the AIP cycle.
- [ ] Implement any backlog features.
  
### Mapping Data Changes
- [ ] Make necessary changes to the Standard Routes, as defined in [the SRC repository](https://github.com/vatnz-dev/vatSys-SRC-Reader/blob/dev/Routes/Routes.xml)
- [ ] Using the Standard Route mapper, generate the vatSys Map Layers and copy to the dataset repository.
- [ ] Using the Standard Route mapper, generate the public `stdRoutes.json` file for external use and commit to the [std-rte-public repository](https://github.com/vatnz-dev/std-rte-public).  Notify Navigraph that the export has been made.

### Testing
- [ ] Test vatSys and EuroScope using the sweatbox environment.
- [ ] Make sure all data files are valid, returning no  ML errors.

### Release
- [ ] Merge content into Master Release Repo
- [ ] Publish Client Data Release.
- [ ] If necessary, publish SOP changes.
