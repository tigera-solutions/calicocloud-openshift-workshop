## Cleanup this workshop.

1. Delete application stack to clean up any `loadbalancer` services.

    ```bash
    kubectl delete -f demo/setup/dev
    kubectl delete -f demo/setup/acme
    kubectl delete -f demo/setup/storefront
    kubectl delete -f demo/setup/hipstershop/
    kubectl delete ns yaobank
    ```

2. Remove calicocloud components from your cluster.
   - Download the script 
   ```bash
   curl -O https://installer.calicocloud.io/manifests/v3.11.1-1/downgrade.sh
   ```

   - Make the script executable 
   ```bash
   chmod +x downgrade.sh
   ```

   - Run the script and read the help to determine if you need to specify any flags 
   ```bash
   ./downgrade.sh --help
   ```

   - Run the script with any needed flags, for example: 
   ```bash
   ./downgrade.sh --remove-prometheus --remove-all-calico-policy
   
   ```   

3. Delete your managed cluster.

   [Menu](../README.md)
   