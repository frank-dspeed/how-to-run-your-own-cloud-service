# how-to-run-your-own-cloud-service
Tutorial to create a Cloud Service Provider

## Create Something to Get Computes
The Core of a Cloud Service Provider are Compute unites that did not change
The Compute can be anything that fits the performance needs of the indipendent cloud parts

## Form Regions of the Computes
you need to group computes by region as network latency is limited by region its importent
to understand that. There are Physical Limits.

## DNS
You need to use and offer DNS Services so that you can route all the diffrent components internal and external

## Reverse Proxys (Load Balancer)
You need a lot of diffrent loadbalancer configurations for diffrent application needs some with cache some without some conditional.

## Deploy IAM 
You need a Central Way of Authority to manage Users and Access. Depending on your region count or overall user count you need to shard or cluster that and take care of backups as this is a persistent part also this part has logging costs that need to be considered and managed

## Interfaces
You should deploy a Interface to sign up with IAM that allows to order Compute, and Configure DNS and Loadbalancers

## Rent Compute to Users
Now you own Compute and have IAM so you can Rent Compute to Users

## Rent Hosted Services Based on Usage.
You need to identify Algos For Horizontal Scale of the Service and then offer pricing for them
you need to be able to horizontal scale the service.

## Example Horizontal Scale Compute & Storage & Bandwidth
To Scale Storage you can simply attach more devices to the cluster depending on the used software to store and manage the data. To Scale the Bandwidth of the Users you need to offer caching you can do input output caching.

## offer eventbus
You Should offer a Eventbus this will get used every where. its essential.

## Connections between services
Allow direct connections eventbus based to diffrent Services.























