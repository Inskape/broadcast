# broadcast

A simple library to handle in-app publisher-subscriber methods in Go. 

It allows for a plugin-like system where components can depends on one or more other components and wait for them to signal that they are ready before proceeding (i.e. an API service that waits for the DB connection to be live before starting the API). 