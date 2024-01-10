VideoClipOrganizer
==================

An open source project to manage you video clips - created and downloaded both.

**Update (Jan 2024)**
I thought of this 10 years ago. Since then, things has changed a lot. Today, we do not download but watch the videos online. So, it only makes sense, that this organizer can bookmark an online video(e.g. from youtube) with the desired time index. I can write a note about that bookmark as well. This will be useful when I am watching a video as part of my research of a topic.


## Implemented Features
Nothing as of now. It's only in the planning phase.

## Planned Features

### Video Index
+ Should support multiple sources such as  local folders, network folders and removable drives.
+ Should keep the files in the original location and only catalog them.
+ Should be able to uniquely identify each source and provide visual indication if a source is not currently available.
+ Should read the video metadata from the file and cache it in the catalog database. There should be option to refresh the database.
+ Should allow user to update the video metadata for single file or multiple files (batch update). This update should happen on the catalog database and there should be a batch utility to push these metadata updates in the original video file. So that I can update the metadata quickly and a background process will update the original file while letting me work on the application at the sametime.

### Interface
+ Should look like outlook 2013. There will be three panes - left, middle and center.
+ Left pane will allow mw to choose source, genre and other top level metadata.
+ Middle pane will list videos within the selected source from left pane.
+ Right pane will be devided into two parts - top and bottom. Top will have a video player and bottom will have the metadata editor. Bottom pane may have number of tabs to organize the metadata.

### Metadata Editor
+ Should allow to view/update metadata of single or multiple files.
+ Should update the metadata in the original file in a background process.

### Video Player
+ Should allow to play video inside the app.
+ Should be able to open video in external  video player as well such as Windows Media Player.
+ Should allow me to bookmark various places in the video and add a note to each bookmark. These bookmark will be saved with metadata and should be saved in the original file also.
