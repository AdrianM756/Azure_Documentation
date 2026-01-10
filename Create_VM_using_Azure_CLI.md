## Create VM using Azure CLI

For this demo, we will create a virtual machine using CLI with the following requirements:

1) Create a new Azure Virtual Machine named ```xfusion-vm``` using the Azure CLI.

2) Use the ```Ubuntu2204``` image and set the VM size to ```Standard_B2s```.

3) Make sure the admin username is set to ```azureuser``` and SSH keys are generated for secure access.

4) Use ```Standard_LRS``` storage account, disk size must be ```30GB``` and ensure the VM ```xfusion-vm``` is in the running state after creation.
<br>

```
az vm create \
-g $group \
--name xfusion-vm \
--image Ubuntu2204 \
--size Standard_B2s \
--admin-username azureuser \
--generate-ssh-keys \
--storage-sku Standard_LRS \
--data-disk-sizes-gb 30 \
```
<br>

To check the status of the vm, we can use the following commands:
```
az vm get-instance-view -g $group -n xfusion-vm | grep displayStatus
```
<br>

We should be able to get this result:

<img width="525" height="114" alt="image" src="https://github.com/user-attachments/assets/cadaa96a-56c3-4d23-9974-189e73ece601" />
<br>



