# [Command] _network vnet subnet list-available-delegations_

List the services available for subnet delegation.

## Versions

### [2018-11-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2xvY2F0aW9ucy97fS9hdmFpbGFibGVkZWxlZ2F0aW9ucw==/2018-11-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.network/locations/{}/availabledelegations 2018-11-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/locations/{}/availabledelegations 2018-11-01 -->

#### examples

- Retrieve the service names for available delegations in the West US region.
    ```bash
        network vnet subnet list-available-delegations -l westus --query [].serviceName
    ```

- List the services available for subnet delegation. (autogenerated)
    ```bash
        network vnet subnet list-available-delegations --resource-group MyResourceGroup
    ```

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2xvY2F0aW9ucy97fS9hdmFpbGFibGVkZWxlZ2F0aW9ucw==/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.network/locations/{}/availabledelegations 2022-01-01 -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/locations/{}/availabledelegations 2022-01-01 -->

#### examples

- Retrieve the service names for available delegations in the West US region.
    ```bash
        network vnet subnet list-available-delegations -l westus --query [].serviceName
    ```

- List the services available for subnet delegation. (autogenerated)
    ```bash
        network vnet subnet list-available-delegations --resource-group MyResourceGroup
    ```