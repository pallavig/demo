
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

     ```sh
     $ mkdir -p /usr/local/data/tmt/frames/input  
     $ mkdir -p /usr/local/data/tmt/frames/output  
     $ mkdir -p /usr/local/data/tmt/movies/input  
     $ mkdir -p /usr/local/data/tmt/movies/output
     ```
- Copy images in ```/usr/local/data/tmt/frames/input``` directory.
- Copy movies in ```/usr/local/data/tmt/movies/input``` directory.


```sh
$ npm install --save-dev grunt-shell
```

#### Steps for running tests
-------------------------
* Goto the project directory.
* Checkout the demo branch of the project. 
     ```
	 $ git checkout demo
     ```
* Get all dependencies. 
     ```
     $ ./activator update
     ```
* Compile the project.
     ```
     $ ./activator compile
     ```
* Run tests. 
     ```
     $ ./activator test
     ```
