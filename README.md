# NLP Media Search
An implementation of an NLP-augmented media streaming site/application in a similar vein to Netflix or Spotify. This is based on an app concept I created during my Human Computer Interaction course in Georgia Tech's OMSCS.

## The main focal points
### Improve Searchability of Media
Users will be able to input search queries as a natural query, i.e. "Action movies featuring Jackie Chan from China", or as a list of tags. For natural queries, an NLP model will ingest the query and parse it into a list of tags. In the database, each entry for a piece of media will include parameters for Title, Director, Cast, Language(s), Genre, Country of Origin, and a list of tags, all of which can be used to to search for particular media.
### Sharing Media Between Friends and Group Chats
During the needfinding portions of my HCI class, a common pattern emerged; nearly everyone I interviewed said that they would decide whether to give a piece of media a chance if it was recommended by people they knew, family and especially friends. As far as I have experienced, no media streaming platform has a built in function to share pieces of media with others within the app. However, many do have a sharing feature that fulfills this function. A built in friends and messaging/sharing system could make the experience smoother than sharing to separate messaging apps. These could work in a similar way to existing chat apps or narrow functionality to sending a particular media link to a specific friend or group chat without any extra chat functionality.
