# Debian-Hurd-Repos
Aptitude Source Listings
This is a replacement apt sources list for Debian Hurd
Simply copy this repo to your system, rename the old sources.list to sources.list.old and then move the sources.list file from this repo to your /etc/apt/ folder
Once moved, nano your new sources.list and choose which repo you want to pull from by uncommenting the URL lines under each section
After that, exit and save, then apt-get update to pull a listing of all packages available on that repo
It is advised that you first pull your packages from the Snapshot repo, then once you've installed your desired packages, then change repos to whichever source you want.
I have included the Snapshot, Sid, Unreleased, Unstable, and Experimental urls that I could find from the mailing list.
