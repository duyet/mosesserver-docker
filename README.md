# mosesserver-docker
Moses server XMLRPC2 

# Build docker 
```
docker build -t mosesserver .
```

# Run Moses Server

```
docker run -it -p 8080:8080 mosesserver
```

Moses server now available at [http://localhost:8080/RPC2](http://localhost:8080/RPC2)

# Test Moses with Python client

Use client.py to test Mosesserver.

```
python client.py
```
