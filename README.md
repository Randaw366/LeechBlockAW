# LeechBlock NG for Firefox

LeechBlock NG (Next Generation) is a simple productivity tool designed to block those time-wasting sites that can suck the life out of your working day. All you need to do is specify which sites to block and when to block them.

It was originally created by James Anderson and contributors Dario Kolac (graphics) & Robert Gützkow (graphics), and was modifed by Randaw366

## Modifications
The program was modified by Randaw366, to use [ActivityWatch](activitywatch.net) for various forms of tracking

## Settings
To utilize ActivityWatch, set the hostname of the device in options/General menu, and set the address of the server in the same place

Then, choose a block (or more) and check "Use ActivityWatch block" and list the titles of the applications and the buckets/watchers for it to check in the designated locations.
Set the time in hours back that you want to check, and set the required tiem spent on the list

## TODO/Development
I am going to continue working on the plugin, and have the following plans:
- Use aw-client-js for communication with ActivityWatch rather than flat fetching.
- Allow you to choose certain time requirements for each app
- Possibly build an extension or modification to ActivityWatch itself to keep settings and whatnot on that side
- Port to Chrome
- Allow to block after certain amount of time rather than unblock after certain time spent
