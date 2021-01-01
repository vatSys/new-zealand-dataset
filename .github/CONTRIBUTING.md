# Welcome


- [Contributor License Agreement](#contributor-license-agreement)    
- [Contributing](#contributing)        
    - [Contributing to the Dataset](#contributing-to-the-dataset)        
    - [Testing the Dataset, and your changes](#testing-the-dataset-and-your-changes)        
    - [Issue Tracking](#issue-tracking)        
    - [Pull Requests](#pull-requests)            
        - [Pull Request Guidelines](#pull-request-guidelines)


Welcome to the VATNZ Dataset repository. Thank you for offering your help to maintain our Sector Files. This document details the correct processes to follow in order to add your own code to the project.

#### Contributor License Agreement

By submitting code as an individual, you agree that VATNZ can use your ammendments, fixes, patches, changes modifications and submissions in the production of the New Zealand Dataset; and that the ownership of your submissions transfers to VATNZ in their entirety.

## Contributing

### Contributing to the Dataset

If you're comfortable with contributing to Open Source projects on GitHub please ensure you read our expectations for issue tracking, feature proposals and merge requests.

**Please avoid** adding AIRAC related commits until you've seen an issue raised for them. If an AIP Bulletin is released, the Controller Operations Director or a delegated individual will review it and raise an issue for the work to be completed.

### Testing the Dataset, and your changes

At the moment, the only way you can test your changes is by pointing the vatSys Profile to the development version. This can easily be done with [GitHub Desktop](https://desktop.github.com/) or the CLI. By pointing the vatSys Profile selector to the `Profile.xml ` of your development version.

### Issue Tracking

If you require support with the Dataset or vatSys, please utilise the #vatsys-discussion channel in the VATNZ Discord server. Issues specifically regarding the features and functions of vatSys should be directed to the VATNZ Training Team. The GitHub Issue Tracker is for feature requests and bugs concerning the NZ Dataset itself.

When submitting an issue, there's a few guidelines that we request you follow.

* **Search the Issue Tracker** before you submit an issue, as it may already be present. [The Issue Tracker can be found here](https://github.com/vatSys/new-zealand-dataset/issues).

* When opening an issue, please provide as much information as you can to ensure that others are able to act upon the requests or bug report. If you are raising an issue for a bug you have encountered, you should also include how to replicate the bug.

### Pull Requests

We welcome pull requests with fixes and improvements to the NZ Dataset. The features that are free and not assigned to somebody will be marked as "up-for-grabs" in the Issue Tracker, but other improvements are also welcome - please ensure you follow the pull work-flow below. This work-flow is designed to be simple, but also ensure consistency from **all** members.

1. Fork the project.

2. Commit your changes to your forked Repo.

3. **Add your changes to the CHANGELOG.md file**. This can be found in [NEW-ZEALAND-DATASET/.github/CHANGELOG.md](CHANGELOG.md).

4. Push the commit(s) to your fork.

5. Submit a Pull Request (PR) to the master Repo. **See below for PR formatting rules**.

6. Be prepared to answer any questions about your PR when it is reviewed for acceptance.

#### Pull Request Guidelines

* The PR title should describe the change that has been made. 

* The PR description should confirm what changes have been made and how you know they're correct (through testing).

* Include any relevant screenshots to prove the changes work.

* Ensure you link any relevant issues in the merge request, remembering that you can link to the issue using a hash and the issue ID, eg #22.

* When you've submitted a PR, comment on the Issue referencing the pull request in the same method as before, eg #pr-id.

