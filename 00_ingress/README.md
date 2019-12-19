
GKE ingress mandatory yaml

    kubectl apply -f 00_ingress_mandatory.yaml

Use

    curl cluster_ip/apple
    kubectl logs -f apple-app

## References

* https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-ingress-guide-nginx-example.html
* https://kubernetes.github.io/ingress-nginx/deploy
