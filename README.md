# docker-browser-console

Forward input/output from docker containers to your browser


## Reference
[mafintosh/docker-browser-console](https://github.com/mafintosh/docker-browser-console)

By using mafintosh's repo, a user can only console a new container created by the image.
We want to console an existing container.

In order to do this, I modified some libraries in node_modules. So, node_modules directory is also pushed here.

## How to use this repo


Simply clone this repo (node_modules will also be downloaded) and then:

```
cd docker-browser-console
node server.js <container_id>
```

Then, open ```index.html``` in your browser.


# Specially, for AT&T uCPE

To console the container hosted on AT&T uCPE, modify the code in ```docker-browser-console/server.js```, from figure 1 to figure 2:


![img](../img/figure_local_console.png)
