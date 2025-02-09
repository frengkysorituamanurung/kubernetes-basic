<<<<<<< HEAD
### Generating CPU Load for Testing Since Minikube doesn't have much load by default, use this command to add load to a pod:

``` 
kubectl run -it --rm load-generator --image=busybox -- /bin/sh -c "while true; do wget -q -O- http://my-app; done"
```
=======
<h5> Generating CPU Load for Testing Since Minikube doesn't have much load by default, use this command to add load to a pod: </h5>

```
kubectl run -it --rm load-generator --image=busybox -- /bin/sh -c "while true; do wget -q -O- http://my-app; done"
```
>>>>>>> ad57769492f62df2468bb3dc6b179f839dd5f16e
