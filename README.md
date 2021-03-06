"# TagApp"
0.3.0
-UI improvements


"# TagApp"
0.2.4
-Adding missing assets
-Removing default user from login
-UI changes for small screens

"# TagApp"
0.2.3
-Adding missing assets
-Adapting home design for iphone7/6

"# TagApp"
0.2.2
-New resources

"# TagApp"
0.2.1
-UI adaptation fixes
-Changes on home page
-Removing live-view feature

"# TagApp"
0.2.0
-Adapting code to work with API v2

"# TagApp"
0.1.24
-Fix wrong screen state for Project screen
-Match time in green color
-Fix refreshing playback video state
-Change match control button color to Red when match is started
-When starting match if recorder is not started start recorder and match
-Limit team names to 3 letters and capitalize it
-Removing login and exit buttons
-Fixing iOS issue with playback list

"# TagApp"
0.1.23
-Reworking of Home screen design, better flexibility for different screens
-Settings save button will show last screen before entering Settings screen
-Changes in Annotation buttons (height tweaks so all buttons are full width)
-Fix for wrong team id in grid for single team overview

"# TagApp"
0.1.22
-UI Rework
-Adapting UI for small screens
-Redo functionality
-Bugfixes

"# TagApp"
0.1.21
-UI tweaks
-Bugfixes

"# TagApp"
0.1.20
-Minor fixes
-Performance improvements
-Second half calculations
-Fixes for playback video player
-Splash screen fix

"# TagApp"
0.1.19
-Annotation Screen new UI
-New Video functionality

"# TagApp"
0.1.18
-Fixing possible issue with black screen on app load
-Changes UI
-Splitting recorder and match buttons into 2 different functionalities
-Bugfixes
-Fixing project overview bug when only one project was shown always

"# TagApp"
0.1.17
-Fix for sending xml in project overview
-Periodicaly checking recorder state
-Live stream video playing from recorder
-Download event types from recorder when user connects to server
-Start match, End match, Start Recorder, Stop Recorder

"# TagApp"
0.1.16
-Fixing adding player function
-Player picker please just with one click and no continue button, because now you need to click two times
-Project overview
-Sending XML in project overview
-Fixed scoreboard at top
-Filter unwanted event types from recorder
-Save download directory info for project
-Keyboard hiding input field fix
-Continue with tagging while downloading playback
-Deletion and Playing of old video

"# TagApp"
0.1.15
-Fixing bug with one team tagging when event is added for wrong team
-Fixing sending XML when tagging without recorder
-Disable XML sending trough settings

"# TagApp"
0.1.14
-Changes in single team tagging - include latest event list
-Tagging without recorder feature
-Fixing missing events for first/second time, and missing times for those events
-Fixing Undo function where there is event for first/second half
-Bugfixes and improvements

"# TagApp"
0.1.13
-Single team tagging

"# TagApp"
0.1.12
-XML format Changes
-Small bugfixes
-Get event types from recorder
-Load default event types
-Load team names from recorder


"# TagApp"
0.1.11
-Upgrading dev environment to iOS10
-Adapting playback player to work on iOS10
-Sending XML file in email atachment

"# TagApp"
0.1.10
-Exit - go to home screens
-Go to home screen after settings are saved
-Fix for connect to server
-First/Second half tracking with events
-Checking video export state while Playlist modal is shown
-Save which teams are in project
-Event Types = Analysis Dashboard (on home screen)
-Fixed event types edit/delete/add
-Event types reordering
-Changes in UI

"# TagApp"
0.1.9
-Swipe to open menu
-Adaptation to new PSD design
-Editing team name in recorder

"# TagApp"
0.1.8
-Deletion of events from recorder
-UI adaptations
-Enable/Disable live view in settings
-Facebook share button in event list (next to download button)
-Team scores
-Add event button now in color of the team
-UI addaptation for smaller screens (iPhone)

"# TagApp"
0.1.7
-New HOME UI
-Adaptive UI - suitable for smaller devices

"# TagApp"
0.1.6
-First/Second Half
-Facebook share
-Privacy settings

"# TagApp"
0.1.5
-Removed xml file creation

"# TagApp"
0.1.4
-No Live view feature
-Show begin/end date for playback video list
-Playback video list and preview size (so annotations are still available)
-Removed percentage from downloading progress
-Changed live view to -> New project
-Changed how list of setups are shown on home page

"# TagApp"
0.1.3
-Event type duration
-Saving logged in user
-Logout
-Changes in playback functionality
-Event before and event after for export (Recorder)
-Latest events (last 3)

"# TagApp"
0.1.2
-Putting together panofield recorder functionality

"# TagApp"
0.1.1
-Turning on and off player picker
-Sending xml at the end of the recording
-Saving recording data on device

"# TagApp"
0.1.0
New login (camera ip, camera type, recorder ip, recorder type ,username and password)

camera type [ dahua or axis ]
recorder type [ vMix or Panofield ] those are select boxes...

Controlling of camera is working in this version too,
Adding events is possible trough menu, Email settings are in email (you can set subject and email to). You can also define event seconds before, event seconds after (for annotation). When you add event email is sent to (email_to from settings page, default is my email)

Recorder start/stop for vMix is working. (time is also shown like for panofield);
Adding teams and players is working.
Adding event types is working

"# TagApp"
0.0.28
-Annotation email XML message
-Email notification settings

"# TagApp"
0.0.27
-Optimisations
-Offline mode

"# TagApp"
0.0.17 - 0.0.26
-Missing plugins on iOS, phonegap build testing, and emulator testing

"# TagApp"
0.0.16
-Fixing package.json for iOS platform
-Fixing file-transfer error on iOS

"# TagApp"
0.0.15
-More debugging

"# TagApp"
0.0.14
-Same file path for android and iOS

"# TagApp"
0.0.13
-Enabling debug for file upload

"# TagApp"
0.0.12
-Panofield screen adaptaton to new features
-Downloading playback functionality

"# TagApp"
0.0.11
-Changes in UI
-Enabling all recorder functions on Stream screens
-Recording current time
-Show list of exported videos
-Show videos being processed
-Exit to Home screen

"# TagApp"
0.0.10
-Changes in UI
-Back button for Dahua screen
-Control speed of Dahua camera trough settings page
-Play Dahua video from substream

"# TagApp"
0.0.9
-Dahua commands: move while button is pressed
-UI Changes

"# TagApp"
0.0.8
-New app wrapper
-User Support
-Dashboard sample screen

"# TagApp"
0.0.7
-Support for AXIS Camera

"# TagApp"
0.0.6
-Added HLS support for Video server stream.
-Added ptz sample commands for testing controlling from app.

"# TagApp"
0.0.5
-Moved record button (videoserver)
-Added overlay modal window that replaced export events screen (videoserver)
-Added transparency to event buttons (videoserver)
-Removed buttons that we don't need anymore (videoserver)
-Added zoomIn and zoomOut functions (streamcontroll)
