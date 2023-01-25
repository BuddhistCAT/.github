# Buddhist Computer-Assisted-Translation Workflow Overview

## How it works?

This system of working is based on leveraging capabilities found in two technologies, Github and Transifex.

**Github** is the online service where all the project data is stored and where new projects are created. One comes to Github to start new projects, and to export projects into various file formats when they need to be published. Github represents asset management (ingestion, segmenting, publishing).

**Transifex** is the online service where everything between starting a new project and wanting to publish it is handled. Transifex represents translation management. 

Together they represent the entire translation project life-cycle from having the edition of the text to be translated ready for translation to having the translated text automatically formatted in various formats.

## Getting Started

### Requirements

- Github account
- Discord account
- Transifex account

### Step-by-Step

You will first have to do a few things to set things up. These things will have to be done just once. Then after that, you will be able to move onto setting up your first project. Then in the future, you'll just repeat that step whenever you want to start new projects.

#### Things Done Just Once

Assuming you already have Github, Discord, and Transifex accounts. Proceed with the following.

1) Become a member in BuddhistCAT Discord community by clicking [this invite link](https://discord.gg/4auZVfCEkU).
2) Request @aunt or @nt on Discord to add you as a member of BuddhistCAT Github organization
3) Create a Github organization (unless you already have it) where your translation projects will be managed (

**NOTE**: Creating a Github organization is not same as having a Github user account. You must create an organization before you can move to the next steps. If the organization you created is named `myneworg` then for the next step, you have to start in https://github.com/myneworg.

4) In the `Settings` tab of the new organization, choose `Actions` and from there `General`, then under the heading `Workflow Permissions` set `Read and write permissions` and save
5) Do the one-time integration between Github and Transifex following the instructions [here](https://github.com/apps/transifex-integration)

**NOTE:** In order to be able to access the **New Project Template** required for starting new projects as explained in the [HOW-TO: Starting a New Project](https://github.com/BuddhistCAT/New-Project-Template/blob/main/documentation/README.md), you will have to become a member of this Github organization first. Do this before moving forward.

#### Things Repeated for Every Project

6) Create your first project after reading through the documentation titled [HOW-TO: Starting a New Project](https://github.com/BuddhistCAT/New-Project-Template/blob/main/documentation/README.md)

## Support

The best way to get support is on [Discord](https://discord.gg/4auZVfCEkU) or alternative [create a ticket](https://github.com/BuddhistCAT/Home/issues/new/choose).
