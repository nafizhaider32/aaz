# [Command] _nginx deployment certificate delete_

Delete an NGINX deployment certificate

## Versions

### [2022-08-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL25naW54Lm5naW54cGx1cy9uZ2lueGRlcGxveW1lbnRzL3t9L2NlcnRpZmljYXRlcy97fQ==/2022-08-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/nginx.nginxplus/nginxdeployments/{}/certificates/{} 2022-08-01 -->

#### examples

- Certificate_Delete
    ```bash
        nginx deployment certificate delete --certificate-name myCertificate --deployment-name myDeployment --resource-group myResourceGroup
    ```