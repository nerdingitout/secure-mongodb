# Setting up your Red Hat Marketplace Account and Registering your cluster
This github repo is dedicated to show step-by-step prequisites for the tutorial: <a href="https://developer.ibm.com/tutorials/secure-mongo-db-enterprise-on-red-hat-openshift/">Secure MongoDB Enterprise on Red Hat OpenShift</a>. Before joining the workshop, make sure to create your Red Hat Marketplace account and to register your cluster in the Red Hat Marketplace to be able to follow along with the speakers.

## Preqrequisites
- Sign up for your IBM Cloud account – https://ibm.biz/BdfsMb
- Register for the live stream and access the replay – https://www.crowdcast.io/e/secure-mongodb
- Red Hat OpenShift Cluster 4.4 on IBM Cloud. You can get it from
  - URL:
  - Key:
- oc CLI (can be downloaded from <a href="https://mirror.openshift.com/pub/openshift-v4/clients/oc/4.5/">here</a> or you can use it at http://shell.cloud.ibm.com/.
## Create your Red Hat Marketplace Account
- Go to https://marketplace.redhat.com/ and click create account if you don't have one already.
- Select the country where your business is located. If your country isn't available, you can select any of the supportd countries for now.
- Login with your Red Hat account.
## Register your cluster in the Red Hat Marketplace
- From the main page, go to Workspace > Clusters
![Screenshot (178)_LI](https://user-images.githubusercontent.com/36239840/111143990-e7316380-859f-11eb-93e2-1b3a5463fbca.jpg)
- Click 'Add Cluster'
![Screenshot (179)_LI](https://user-images.githubusercontent.com/36239840/111144264-4a22fa80-85a0-11eb-96eb-3d4edf37e2a8.jpg)
- Generate pull secret and copy the commands to your terminal as shown in the page, follow the steps.
![image](https://user-images.githubusercontent.com/36239840/111144479-8d7d6900-85a0-11eb-86de-d62f0fd8c8ea.png)
- If you are using Red Hat OpenShift on IBM Cloud, make sure to reload your worker nodes, and that's by going to Worker nodes page, select all worker nodes and click on Reload as shown below. This step might take a while.
![Screenshot (180)_LI](https://user-images.githubusercontent.com/36239840/111145494-bd793c00-85a1-11eb-83e5-024a6ccf7f86.jpg)
## Next Steps
Now you are set to perform the steps in <a href="https://developer.ibm.com/tutorials/secure-mongo-db-enterprise-on-red-hat-openshift/">Secure MongoDB Enterprise on Red Hat OpenShift</a>
