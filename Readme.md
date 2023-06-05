## This Repository provides to manage CI/CD ML Server on Cloud

## Do

1. Care about the following configuration on deployment and cloud build

2. Choose the right tag version

### How To Git Submodule

```bash
# update to the latest commit version
git submodule update --remote

# fetch and pull for each submodule
git pull --recurse-submodules
```

### How to Dockerize

```bash
# setup .env variables
# run docker compose
docker compose build

docker compose create

docker compos start / up
```

### How to Kubernetes

```bash
# create cluster in single zone
gcloud container clusters create ml-server-k8s \
	--num-nodes 1 \
	--machine-type n1-standard-1 \
	--disk-size 10 \
    	--zone asia-southeast2-a

```
