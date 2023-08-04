You need to do the following before running `kubectl apply -f app-deployment.yaml`

```
sudo -i
swapoff -a
exit
strace -eopenat kubectl version
```
