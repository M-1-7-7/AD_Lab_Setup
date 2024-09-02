# WKS Images
1. get a ISO from the microsoft evaluation center [evaluate-windows-server-2019 ](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise) or whaterver version is applicable
2. Set up in VMware workstation
- New Virtual Machine > Typical `next` > Selct the ISO `next` > no product key `next` > select install location `next` > 60GB, Multiple files `next` > power on after creation **DESELCT** `next`
- before first power on go to Edit Virtual macine settings > from hardware remove floppy disk > set resources for the device > Set netowrk to NAT > click ok


### VM First Use
1. Deploy the virtual machine for the first time
- power on machine > when promted with `Which type of installation do you want` select `Custom` > when promted with `where do you want to install windows` select `New` `apply` and it should split the drive into multiple partitions > click `next`
2. Computer will restart and it will bgin the process of setting up an account and basic config
- click through insall prompts until you see `Sign in with Microsoft` > select `Domain join instead` > set up a local user > continue through setup

### Conect VM to Domain

### Create Local Administrators

### Start Serivices
