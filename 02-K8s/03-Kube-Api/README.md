   ```
   48  kubectl  get pods -n kube-system
   49  cd /etc/kubernetes/
   50  ls
   51  cd pki/
   52  ls
   53  ls -ltr etcd/
   54  ls
   55  cd ..
   56  ls
   57  cd manifests/
   58  ls
   59  vim kube-apiserver.yaml 
   61  kubectl cluster-info
   62  kubectl  get nodes 
   63  kubectl cluster-info
   64  kubectl version 
   65  kubectl api-versions
   66  ls
   67  d 
   68  cd 
   69  ls
   70  cd docker-eks-verizon-14-March-22/
   71  ls
   72  cd 02-K8s/
   73  ls
   74  cd 01-First-App/
   75  ls
   76  vim nginx-pod.yaml 
   77  kubectl api-versions
   78  kubectl api-resources 
   79  kubectl  run hello-k8s --image=nginx --dry-run -o yaml 
   80  curl 172.31.0.100:6443
   81  curl https://172.31.0.100:6443
   82  curl https://172.31.0.100:6443 -k 
   83  kubectl proxy --address='172.31.0.100' --port=8080 --accept-hosts='.' --accept-paths='.' &
   84  curl http://172.31.0.100:8080 -k 
   85  curl http://172.31.0.100:8080/api 
   86  kubectl  get pods -o wide 
   87  ps -ef | grep -i proxy 
   88  kill -9 17702
   89  ls
   90  kubectl  get pods 
   91  cat ~/.kube/config 
   92  kubectl config view
   93  kubectl config get-contexts 
   94  ls
   95  kubectl config get-contexts 
   96  ls
   97  cd /etc/kubernetes/
   98  ls
   99  cd pki/
  100  ls
  101  kubectl get sa 
  102  cd ..
  103  ls
  104  cd 
  105  ls
  106  cd docker-eks-verizon-14-March-22/
  107  ls
  108  cd 02-K8s/
  109  ls
  110  mkdir 03-Kube-Api
  111  ls
  112  cd 03-Kube-Api/
  113  ls
  114  history > README.md
```
