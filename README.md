
## Streaming library



#### Steps for data setup
-------------------------
- Create directory structure using following commands :-     
     ```sh
     $ mkdir -p /usr/local/data/tmt/frames/input
     $ mkdir -p /usr/local/data/tmt/frames/output
     $ mkdir -p /usr/local/data/tmt/movies/input
     $ mkdir -p /usr/local/data/tmt/movies/output
     ```

- Copy images in `/usr/local/data/tmt/frames/input` directory.
- Copy movies in `/usr/local/data/tmt/movies/input` directory.



#### Steps for running tests
-------------------------
* Goto the project directory.
* Checkout the demo branch of the project. 
     ```sh
     $ git checkout demo
     ```

* Get all dependencies. 
     ```sh
     $ ./activator update
     ```

* Compile the project.
     ```sh
     $ ./activator compile
     ```

* Run tests. 
     ```sh
     $ ./activator test
     ```
