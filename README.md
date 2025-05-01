<div align="center">
<img src="https://cdn.discordapp.com/icons/805335928289624074/a_927dfe90d7d14c3f0af3d9d9f30d4226.gif?size=1024" width="100" height="100"> </img> 

# VR-Cat
  
<br>
</div>
VR-Cat is a Discord bot designed for VRChat group owners to provide information and assist with group moderation. 

<br>
Developed by Yen and the After Hours Development Group.  

## What does the bot do?
The VR-Cat bot mirrors your group's audit log, posting it within your Discord server so that your staff can apply evidence and tags to each interaction. 
The bot also serves to give insight into your group, such as generating Instance, group members and moderation analytics.
# Automatic audit logging:
VRCat spawns channels that can be used to record kicks, bans, unbans, warns, joins, and leaves in forum channels. This allows group staff members to tag each interaction, and add evidence that the files are not downloaded but based on Discord's file lifetime. Posts will auto-archive after the set time that your group has established, for example, kicks will be automatically archived after 72 hours. 

# Commands:
## `/ban`
Ban does as it says; when you provide a VRChat user's ID, it will ban the user from your group. 
## `/unban`
Unban users who were previously banned when provided with a VRChat User ID. 
## `/user` 
This command, when provided with a VRChat User ID, displays their VRChat profile, the groups they have set to public, and their moderation counts, such as the number of times they have been kicked from your group or other groups. However, if you use this command on a staff member for your group, it will also show their total recorded moderation actions they've taken. 
## `/auditlookup`
When provided with a VRChat User ID, this command will bring up all evidence the group has stored on that person, showing how many times theyve been kicked or banned and why they where previously kicked or banned.

## Staff auditing:
By typing in the command `/analytics` you can choose from the following options:
### `staff audit`
A CSV of moderation taken over the past 4 weeks, a small overview on staff stats over 72 hours, 1 week and 1 month, with a graph that shows the upper and lower 50% quartiles.
For example:
Discord message preview    |  Graph Larger View
:-------------------------:|:-------------------------:
<img src="https://github.com/User25514/VR-Cat/blob/main/ExamplePicture/StaffAuditMessageExample.png" width="300" height="900"> </img> | <img src="https://github.com/User25514/VR-Cat/blob/main/ExamplePicture/StaffAuditModerationGraphExample.png" width="1300" height="900"> </img> 

## `Instances`
This will record how many users are inside your instances, regardless of the number of worlds you use. This can be used to test out worlds and see which ones are better for your community. 
This command will also give insight into the diversity of your instances, showing how many PC, Quest, and ios users are in your instance. 

Discord message preview    |  Graph Larger View
:-------------------------:|:-------------------------:
<img src="https://github.com/User25514/VR-Cat/blob/main/ExamplePicture/InstanceCountExampleMessageDivrsity.png" width="372" height="305"> </img> | <img src="https://github.com/User25514/VR-Cat/blob/main/ExamplePicture/InstanceCountExample.png" width="1400" height="600"> </img> 

## `Join and Leaves`
This option shows the Join and leave rates over 6 months, indicating member retention and periods with an influx of members, such as during events. 
<img src="https://github.com/User25514/VR-Cat/blob/main/ExamplePicture/joinandleaveExample.png" width="1400" height="600"> </img> 
