1. You plan to deploy an application gateway named AppGw01 to load balance internal IP traffic to the Azure virtual machines connected to subnet0. You need to configure a virtual network named VNET01 to support the planned application gateway. You plan to create App Service WabApp01, which you can scale horizontally. Solution should use lowest priced app Service Plan. You plan to connect application gateway AppGw01 to the app service WebApp01
    •  Ensure that an app service WebApp01 can only receive traffic from a specific application gateway instance AppGw01
    •  Allow HTTPS over TCP port 443 to Web01 and to prevent HTTP over TCP port 80 to Web01. 

![resources](https://github.com/ivnovyuriy/task-azure-43/blob/15487a02eb03303fc7df543a52670e4b008f6ad6/img/resources.png)

![deny](https://github.com/ivnovyuriy/task-azure-43/blob/15487a02eb03303fc7df543a52670e4b008f6ad6/img/deny.png)

3. ** You need to automate previous tasks utilising IaaC tools of your choice (For e.g. Terraform).

![infra](https://github.com/ivnovyuriy/task-azure-43/blob/15487a02eb03303fc7df543a52670e4b008f6ad6/img/infra.png)

![output](https://github.com/ivnovyuriy/task-azure-43/blob/15487a02eb03303fc7df543a52670e4b008f6ad6/img/output.png)