## Copy Data to an Azure Blob Storage Container

Copying Data to an Azure Blob Storage Container refers to the process of moving or duplicating files (also known as blobs) from a source location like a local computer, another cloud provider, or a different Azure service into a specific container within an Azure Storage account.
<br>

## Demo

On this demo, a blob container named ```datacenter-blob-18514``` already exists in the ```centralus``` region under the storage account ```datacenterst16831```. Copy the file ```/tmp/datacenter.txt``` to the Blob container ```datacenter-blob-18514```. To do this, we will be using the Azure CLI.
<br>

First, we will need to go to the storage account ```datacenterst16831``` > containers > then select ```datacenter-blob-18514```.

<img width="1103" height="509" alt="2026-05-17_19-48" src="https://github.com/user-attachments/assets/c71c53b0-099d-432b-b578-8254277e4535" />
<br>

<img width="622" height="455" alt="2026-05-17_19-52" src="https://github.com/user-attachments/assets/ec8812a0-a6b8-4af7-9f8f-5fb37900a39b" />
<br>

On the Azure CLI, navigate to ```/tmp``` directory.

```
cd /tmp
```
<br>

To list all storage accounts in the current Azure subscription or a specified resource group, we will use the command:

```
az storage account list
```
<br>

We will then upload the copy of  ```/tmp/datacenter.txt``` to the blob container ```datacenter-blob-18514

```
az storage blob upload --account-name datacenterst16831 -c datacenter-blob-18514 -f /tmp/datacenter.txt
```
<br>

To verify, we can go and check the blob container.

<img width="746" height="394" alt="2026-05-17_20-03" src="https://github.com/user-attachments/assets/a754dde2-5a43-44aa-9544-1aa720d37fa7" />
<br>








