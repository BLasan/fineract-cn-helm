# Creating Helm Chart

1. `helm dep up fineract-cn`

2. `helm package fineract-cn`

3. `helm repo index .`

4. `sh kubectl-start-up.sh`

5. `helm install fineract-cn ./fineract-cn/ --namespace="fineract-cn" --create-namespace`