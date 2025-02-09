<h5> Generating CPU Load for Testing Since Minikube doesn't have much load by default, use this command to add load to a pod: </h5>

```
kubectl run -it --rm load-generator --image=busybox -- /bin/sh -c "while true; do wget -q -O- http://my-app; done"
```
