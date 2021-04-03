# VATNZ Dataset Contribution Guidelines

  - [**1. Introduction**](#1-introduction)
    - [1.1 Contributor License Agreement](#11-contributor-license-agreement)
  - [**2. Contributing**](#2-contributing)
    - [2.1 General Overview](#21-general-overview) 
    - [2.2 Issue Tracking](#22-issue-tracking)
      - [2.2.1 Opening a new Issue](#221-opening-a-new-issue)
    - [2.3 Forking the Repo](#23-forking-the-repo)
    - [2.4 Submitting a Pull Request](#24-submitting-a-pull-request)
    - [2.4.1 Guidelines](#241-guidelines)<!-- /TOC -->

<!-- End TOC -->

## 1. Introduction

Welcome to the GitHub repository for the New Zealand Dataset. Thank you for taking an interest in maintaining our Dataset. This document details the correct processes to followin order to add your own code to the project.

This document assumes you have some knowledge about how git works, and how GitHub works specifically. You should be comfortable with forking repositories, committing code to that repository, and then creating pull requests.

### 1.1 Contributor License Agreement

By submitting code to this project you agree that VATNZ can use your ammendments, fixes, patches, changes or modifications in the production of the New Zealand Dataset; and that ownership of your submissions transfers to VATNZ in their entirety.

## 2. Contributing

### 2.1 General Overview

The Dataset repo follows GitHub best practice, with changes being made outside of the master repository and merged via pull request. This ensures adequate compartmentalisation of different development versions, with only the stable current release ever being present in the master branch. 

The Dataset repo currently has a few different branches -
- `master` - the master release repository for the project
- `airac-wip` - where changes for the next AIRAC release are staged. This is the active development branch.
- `position-rewrite` - part of a larger optimization of backend positions, in addition to the addition of Tower control zones.

### 2.2 Issue Tracking

Our repository uses the built-in GitHub Issues system to monitor changes made to our Dataset. This ensures that every commit made can be adequately traced. 

Users of the Dataset are more than welcome to open an Issue for a feature or issue they want to be addressed. 

#### 2.2.1 Opening a new Issue

When opening a new issue, we ask that you follow these very simple guidelines -

- **Search the Issue Tracker before you submit an issue**, as it may already be present. 
- **Provide as much information as you can**. If this is a request, then should be providing references to the changes. 
- **If you are filing a bug report**, please provide the current build number of your vatSys client and your `error_log.txt`. This can be found in your `User\Documents\vatSys Files\` directory.

### 2.3 Forking the Repo

As stated above, we do not allow direct commits to the `master` branch. All changes are to made to the `airac-wip` branch, where it can be evaluated by the Operations Director prior to release.

When forking the repo, we ask that you fork the `master` branch, as this will be the most stable platform for you to work from. 

### 2.4 Submitting a Pull Request

#### 2.4.1 Guidelines 

Submitting your Pull Request is no different from submitting any other PR. Ensure that you are submitting a PR from your repo to the `airac-wip` branch of our repo. 

- The title of the PR should reference the Issue number of the problem you're solving. It should be succint and accurate. 
- You should use action words within your title. Using words such as `Fixes` or `Closes` will automatically close the Issue apon merge and their usage is desirable. 
- Throughout your development of the issue, you should have been updating the original Issue the best you can. Before you submit your PR, you should include a summary of testing you've carried out to ensure that the issue has been rectified. This should include screenshots if applicable.
  
**Example of a good Pull Request title**

`(Fixes #67) Removal of Miranda (RD) NDB, replaced with waypoint MERAS.`