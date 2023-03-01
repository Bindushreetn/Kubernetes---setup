# Installing etcd:
## What is etcd?
- etcd is an open source distributed key-value.

### Why it is used?
- Kubernetes uses etcd as its database.
- It is used to store, hold and manage the critical information that distributed systems need to keep running. Most notably, it manages the configuration data, state data, and metadata for Kubernetes, the popular container orchestration platform.

### Procedure to Install etcd:
- This needs to be installed on Kubernetes Master Machine. In order to install it, run the 
following commands.

1. ``$ curl -L https://github.com/coreos/etcd/releases/download/v2.0.0/etcd
-v2.0.0-linux-amd64.tar.gz -o etcd-v2.0.0-linux-amd64.tar.gz``

2. ```$ tar xzvf etcd-v2.0.0-linux-amd64.tar.gz```

3. ```$ cd etcd-v2.0.0-linux-amd64```

4. ```$ mkdir /opt/bin```

5. ```$ cp etcd* /opt/bin```

In the above set of command:
- First, we download the etcd. Save this with specified name.
- Then, we have to un-tar the tar package.
- We make a dir. inside the /opt named bin.
- Copy the extracted file to the target location.
