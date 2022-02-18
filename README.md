# FHE-Implementation

An implementation of homomorphic encryption scheme in c++ using the pallisade library.

This project is made for educational purposes to learn the various functions present in the pallisade FHE library and using it to make a server based application that takes in user input as vectors and performs certain computaions/bit shifts on encrypted data where the user specifies the action to be performed.

For installing pallisade first [install docker](https://docs.docker.com/engine/install/) in your system then run the dockerfile given above

For running the docker file execute the following commands stepwise:

> ***It will take some time for the docker image to be built please be patient :)***

```bash
sudo docker build -t encrypted-operations .
```
```bash
sudo docker run -d -p 1221:1221 --rm encrypted-operations
```

For the detailed writeup for this project refer the [blog post](https://vishvesh-rao.github.io/posts/Encrypted-Operations-InCTFi21/)
