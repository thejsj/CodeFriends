## Mongo to RethinkDB Migration

1. server/file/downloadController.js
- File uses a `submitAsync` function which is part of LiveDB
1. DONE server/file/fileController.js
- File uses Mongo in 2 places to get/set file structure of a project
1. DONE server/file/uploadController.js
- File uses a `submitAsync` function which is part of LiveDB
1. DONE server/chatServer.js
- Chat room table names are note being created. Will throw an error.
1. DONE server/deleteAllDatabases.js
1. DONE server/liveDbClient.js
- Uses the RethinkDB/MongoDB Live DB client module

## TODO

1. Close connections
2. Create global r file

