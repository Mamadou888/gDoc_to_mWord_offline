# Google Doc to Microsoft Word Offline Sync
> Mamadou-Sadio Diallo (mamadou)

## Overview
A python script that syncs word files locally on my computer to a specific folder in my google drive

## Background
This is such a first word problem but something I really wanted to see exist. I always find myself in sitations where I want to work on documents I'd written in Google Drive, but I don't have access to the internet. Google Drive offline refuses to work. I also like to use Microsoft Word when I'm working offline. My hope is that this script will be able to sync a folder with Microsoft Word files with a specfic folder in my Google Drive. 

## Implementation
In order to implement this, I'll need to learn to use to the DRIVE REST API. Much of the work will involve converting Drive to Word and storing it specfically somewhere in my desktop. 

## Tasks
1. Connect with Drive API
2. Figure out how to read and write to local files
3. Figure out how to add and remove files in Google Drive
5. Have the script run in the background so it'll "Sync" live
6. *(stretch)* host the script on the internet so I don't have to run it on start-up
7. *(stretch)* figure out a way to seamlessly have me choose what folder to sync the drive folder with. Or vice versa

I think the first 3 tasks are completely doable and I have the knowledge, thanks to this class, to make them happen.

## Resources
I'll be using many requests to the DRIVE Api. Maybe I'll have to host this web app on a server, I was thinking Amazon Web Services, mainly because I have a coupon for it. 

-- CS41 Final Project --
