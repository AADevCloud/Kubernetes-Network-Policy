# Kubernetes-Network-Policy
### To Implement the Network Polciy in Kubernetes Enviornmetns you can implement the one the following network solution 
Install a Network Policy Provider https://kubernetes.io/docs/tasks/administer-cluster/network-policy-provider/
- Kube-router
- Calico
- Romana
- Wave-net

Install a Wave-net Network Policy https://github.com/weaveworks/weave/blob/master/site/kubernetes/kube-addon.md#network-policy

- Weave Net can be installed onto your CNI-enabled Kubernetes cluster with a single command:
```bash
kubectl apply -f https://github.com/weaveworks/weave/releases/download/v2.8.1/weave-daemonset-k8s.yaml    
```
