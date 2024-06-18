Done
For further reference, you can check the code [HERE](https://github.com/asadsaves/asad-go-lang.
).
The background management interface of BFS.

Initialization Process (please refer to test/ops_initialization.py):
Step 1
Start the store, directory, proxy, and pitchfork services. After starting the store, ZooKeeper should display store nodes under /rack.

Step 2
Call the space() function to initialize the store. Once this is complete, disk space will be allocated and the BFS storage directory will contain generated volume files.

Step 3
Call the groups() function to group the stores. After this step, ZooKeeper should display group nodes under /group/.

Step 4
Call the volumes() function to activate the volumes. Upon completion, ZooKeeper should display volume nodes under /volume/.

