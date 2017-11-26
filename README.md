# PlexGuide.com - Version 4

<p align="center">
  <img src="https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/blob/Version-4/scripts/plexguide.PNG" alt="PlexGuide.com Logo"/>
</p>

<p align="center">
  <img src="https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/blob/Version-4/scripts/plexguide-demo2.PNG" alt="PlexGuide.com Logo"/>
</p>

### Info
- Written By Admin9705 and Deiteq
- Reddit Link (Great for Discussion): http://reddit.plexguide.com
- **Note:** If you have issues, please post them in ISSUES for **BETTER** Tracking.

### Want to Donate? Everybit Helps!

- Bitcoin : 1H3SD3ef6qaN8ND8S8ZQCaEyD4pMW4kFsA
- Ethereum: 0xe40ED5eA14e20e7dc4595FdE195526d36308cF04
- LiteCoin: LbCDaq26N39TuUarBkrxTXNFjsNWds9Ktj

### Mission Statement & Purpose

Build an operational-automated server that mounts your Google Drive, while utilizing various tools and Plex.  Purpose is to combat the poor performance of the Plex Cloud and issues in regards to the Google API Bans.  

### Required

UB 16/17 & Google Drive (https://gsuite.google.com)
- ***Never*** buy an EBay Google Account! Buy your own. Sellers own your information and **YOU DO NOT CONTROL IT**
  - [Article 1](https://community.ebay.com/t5/Bidding-Buying/Seller-of-Google-Drive-Unlimited-Storage-problem/td-p/27058292) | [Article 2](https://www.reddit.com/r/PleX/comments/6crdjv/google_is_disabling_certain_gsuites_accounts/)
  
- Ignore the 5 User Requirement on EBay; I know... you will get anxiety. Unlimited works with 1 account; don't ask, just listen!

### Structured For

PlexGuide is structured and confirmed to work on Dedicated Server, VPS, VMWare (using Ubuntu from the main site) and is set to be used on a NEW SERVER.  If you are attempting anything other than this, you can test... but may have issues.  Support for anything other than this will be ignored.  

### Really New To Linux?
It's ok! If you mess up something, reinstall and try again.  See what if your actions was a mistake or a bug.  If so, document it and post in the issues.  When known, we update the guides to help others!  Remember, you only learn through frustration... but alot has been eliminated for you to make your life easier.  

### Preparation, Installation & Configuration 
Note 1: Follow up the entire PlexGuide Wiki @ http://wiki.plexguide.com
Note 2: Do you know that if you log on to GitHub, you can edit the wiki pages?! Yes, you can make correctons or expand upon it AUTOMATICALLY. IF you make updates, it will save us a lot of time!

**A. Preparation:**
 1. [Google Drive Layout](https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/wiki/Google-Drive-Layout)
 2. [Do you Require SSH Access?](https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/wiki/Access-via-SSH)
 3. [Do you Require a SUDO User?](https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/wiki/Creating-a-SUDO-User)
 4. [Disk Space Warning Check!](https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/wiki/Disk-Check-Warning!)
 
**B. Install Instructions:**

Install GIT
```sh
sudo apt-get install git
```

To Install PlexGuide
```sh
sudo git clone https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server.git /opt/plexguide
sudo bash /opt/plexg*/sc*/ins*
```

To Execute PlexGuide in the future, type:
```sh
plexguide
```
  
**C. Configuration**
 1. Install & Configure Either the [RClone Unencrypted Version](http://unrclone.plexguide.com) or the [RClone Encrypted Version](http://enrclone.plexguide.com)   
 2. [Configure PlexDrive](http://plexdrive.plexguide.com)
 3. [Configure Plex](http://plex.plexguide.com)
 4. [Configure Programs](http://wiki.plexguide.com) on the ***Right Hand Side***
 5. [Configure Portainer](http://portainer.plexguide.com)
 6. [Port Numbers Reminder](https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/wiki/Port-Assignments)

### Final Note
See issues or have solutions? Please post your [GitHub Issues for the Best Tracking](https://github.com/Admin9705/PlexGuide.com-The-Awesome-Plex-Server/issues) or [REDDIT](http://reddit.plexguide.com).  Your feedback helps us and you!
