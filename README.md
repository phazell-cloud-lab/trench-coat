# trench-coat
Generic API wrapper for running applications on a server, listens on a port, then runs sub-processes on the server.
Initially intened for 'lift n shift' containerisation activities as the compiled go binary can sit alongside the apps in the image.


## Brainstorms
- Behavour determined by a yaml file.

- [ ] Simple example - trigger a bash script, return output.  
- [ ] Long running example - what if the programme takes a while?  
- [ ] Stream example - can we stream output back to the client?  
- [ ] Auth methods - eg Bearer tokens, JWT, client certificates?  
