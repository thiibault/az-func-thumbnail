---
title: run page
layout: template
filename: RUNPAGE.md
--- 

## let's see steps by steps :

### create storage && ressource groupe :

1. Go to your storage account.

2. Then create a ressource groupe for your project, like :
    (all your next services will be define into it and in the same region !)

![alt text](./images/CE-ressource-groupe.png)

2. Create a storage account and containers :

storage account :
![alt text](./images/CE-createSA.png)


containers 2 with blob access:
- images => inputs:
- thumbnail => outputs:
![alt text](./images/CE-createcontainer.png)


### create azure function && links :

1. create azure function :
- in your region 
- in your ressource groupe 

![alt text](./images/CE-create-function.png)

- hosting in your storage account.
![alt text](./images/CE-function-hosting.png)


