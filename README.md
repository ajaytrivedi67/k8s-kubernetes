#kubernetes nginx ingress controller, sample application with ingress resource. This is for Cloud K8S clusters like AKS, EKS or GKS

It has 2 folders one has ingress-controller and other has sample application with ingress resource

$ kubectl apply -f ingres-nginx

$ kubectl apply -f sample-application

The above command will create the nginx ingress controller, deploy the sample application with ingress-resource. It will create the LB which you need to point in the DNS (Route 53) as CNAME
