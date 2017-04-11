**docker-sigsci**

Docker image for running a standalone signal scienes agent

**Usage**

```sh
docker build -t retracedhq/sigsci .
```
```sh
docker run -d \
 -e SIGSCI_RPCADDRESS="unix:/var/run/sigsci/" \
 -e SIGSCI_HOSTNAME=docker-test \
 -e SIGSCI_ACCESSKEYID=...  \
 -e SIGSCI_SECRETACCESSKEY=... \
 retracedhq/sigsci
```
