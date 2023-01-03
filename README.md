1. You plan to deploy an application gateway named AppGw01 to load balance internal IP traffic to the Azure virtual machines connected to subnet0. You need to configure a virtual network named VNET01 to support the planned application gateway. You plan to create App Service WabApp01, which you can scale horizontally. Solution should use lowest priced app Service Plan. You plan to connect application gateway AppGw01 to the app service WebApp01
    •  Ensure that an app service WebApp01 can only receive traffic from a specific application gateway instance AppGw01
    •  Allow HTTPS over TCP port 443 to Web01 and to prevent HTTP over TCP port 80 to Web01. 

![resources](https://github.com/ivnovyuriy/task-azure-42/blob/abbdf058b0d51c60b47819bb69c354c4c1e62574/screenshots/resources.png)

![deny](https://github.com/ivnovyuriy/task-azure-42/blob/abbdf058b0d51c60b47819bb69c354c4c1e62574/screenshots/deny.png)

3. ** You need to automate previous tasks utilising IaaC tools of your choice (For e.g. Terraform).

![infra](https://github.com/ivnovyuriy/task-azure-42/blob/abbdf058b0d51c60b47819bb69c354c4c1e62574/screenshots/output.png)