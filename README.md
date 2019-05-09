# proxy-fun
A little experiment of using a proxy with node.js.

## To run:
1. Run ./run-in-docker.sh.  This will set up a command prompt in a docker container.  Note that this script assumes a Unix environment (it uses the `pwd` command to get the current directory).
2. Run /proxy/start-proxy.sh.  This will run the node.js proxy.
3. From a web browser, access http://localhost:8000.  This will demonstrate that the proxy is working.

