# SST

Parse the url and display the content of JSON as per the assignment: https://gist.github.com/maclir/f715d78b49c3b4b3b77f

Highlights of the Assignment:
- Supports iOS versions 8 and above
- Supports both iPhone and iPad devices
- Integrated cocoapods to install third party libraries
- Installed popular AFNetwork library (https://github.com/AFNetworking/AFNetworking) for network communications
- Implemented custom collection view flow layout to display items in a screen which is well suited in iPad
- Implemented service wrapper class for network API communications on top of AFNetworking which has following features: 
1. Parse the response and callback with respective class objects
2. Store and retrieve url responses from/to the files
3. Handle duplicate API requests

Some of the iOS concepts used in this assignment:
- Auto layouts
- Adaptive layouts
- Storyboards
- Datasources/Delegates
- Notifications
- Operation Queues
- Blocks
- Singleton Class
- Collection views/custom cells
- Custom collection view flow layout
- Categories

This assignment has been implemented based on Obj-C design pattern MVC and considering measures like scalability and performance.

The following improvements can be done:
- Loading indicator until data loads
- Animations
- Launch image
- Size classes for different layouts
- Unit test cases

NOTE: Open Saltside.xcworkspace file instead of Saltside.xcodeproj in the SST/Saltside folder from Xcode to run the app as we integrated cocoapods.
