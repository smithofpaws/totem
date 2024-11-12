# totem
A simple software to control and display information on a screen.

# Basics
The sofotware works by adding .json files that follow defined key specifications. For example, a file with a key named "video_sunset" is interpreted as a video file and its children keys will define its behavior. An example file structure is as follows:
```
{
  "video_1": {
    "file": "/sunset.ogv",
  },
  "image_dog": "/dog.png",
}
```
