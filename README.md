# helmpoc
A basic PoC (still WIP) on using HELM (HELM3) with AKS

## HELM3 reference
Install helm: https://helm.sh/docs/intro/install/ <br />
tutorial at -- https://www.youtube.com/watch?v=eNqjoX20BH4&list=PLLYW3zEOaqlKYku0piyzzLFGpR9VpPvXR&index=3 <br />

helm create mychart <br />
helm lint ./mychart/ <br />
helm install --dry-run --debug ./mychart/ --generate-name <br />
helm install <name> ./mychart/ <br />
helm list <br />
helm uninstall <name> <br />

