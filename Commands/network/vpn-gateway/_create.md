# [Command] _network vpn-gateway create_

Create a site-to-site VPN gateway.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL3ZwbmdhdGV3YXlzL3t9/2022-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/vpngateways/{} 2022-05-01 -->

#### examples

- Create a site-to-site VPN gateway.
    ```bash
        network vpn-gateway create -n MyVPNGateway -g MyRG --vhub MyVHub -l westus
    ```
