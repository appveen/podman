# Podman images


```
docker pull appveen/podman:TAG
```

```
docker run --privileged -v /tmp/podman:/var/lib/containers appveen/podman:latest \
run alpine echo hello from alpine in podman container
```

```
docker run --rm --privileged -v /tmp/podman:/var/lib/containers -it --entrypoint=/bin/sh appveen/podman:latest
```