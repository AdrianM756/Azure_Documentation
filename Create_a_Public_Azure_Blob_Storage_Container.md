## Create a Public Azure Blob Storage Container

On this demo, we will create a Public Azure blob storage container.

For this, we will create a new storage account. We can see that it is available on the main dashboard.

<img width="1106" height="227" alt="2026-04-25_18-28" src="https://github.com/user-attachments/assets/17122a60-0136-4eec-a5e3-6b60d2c83b66" />
<br>
<br>

Once we navigate, we will then select ```create```.

<img width="314" height="277" alt="2026-04-25_18-31" src="https://github.com/user-attachments/assets/fe8d5475-69e3-489f-858f-defe6afbd238" />
<br>
<br>

For the account name, indicate your desired name of for the account. For the storage type, we will select the azure blob storage. Once seetled, click on ```Review + create```.

<img width="804" height="894" alt="2026-04-26_19-38" src="https://github.com/user-attachments/assets/1c9d1a3e-5b97-4b69-a252-2575c730bf03" />
<br>
<br>

Once created, go to resources then select the storage account that we've just created.

<img width="669" height="488" alt="2026-04-26_19-43" src="https://github.com/user-attachments/assets/b4b817f8-51f1-4426-8860-7f744361946e" />
<br>
<br>

Go to ```Data Storage``` > ```Containers```.

<img width="278" height="516" alt="2026-04-26_19-41" src="https://github.com/user-attachments/assets/3688ad95-5316-49cb-a42e-a1ab2824bdf5" />
<br>
<br>

Click ```Add containers```.

<img width="422" height="88" alt="2026-04-25_18-42" src="https://github.com/user-attachments/assets/309c2f7f-62b4-4cc4-99df-fb0e5992fb85" />
<br>
<br>

For this, you can name it as you desire then click ```Create```.

<img width="435" height="927" alt="2026-04-25_18-43" src="https://github.com/user-attachments/assets/3a8ba6ff-8ea4-4511-a0db-f1d139997dd5" />
<br>
<br>

## Make it available in Public

Under the storage account, navigate to ```Settings``` > ```Configuration```.

<img width="258" height="795" alt="2026-04-26_19-49" src="https://github.com/user-attachments/assets/11f38a67-cec0-40e8-9b26-50ac92119bd0" />
<br>
<br>

Enable the ```Allow Blob anonymous access``` then click ```Save```.

<img width="473" height="139" alt="2026-04-26_19-50" src="https://github.com/user-attachments/assets/2661d776-b43d-4404-8d39-1c38ad4ad40d" />
<br>
<br>

Go back to the ```Containers``` section. Check the box on the container that we've created then select ```Change access level```.

<img width="564" height="230" alt="2026-04-26_19-53" src="https://github.com/user-attachments/assets/b3c3285e-0cc6-45d8-a600-f51f3c8a69de" />
<br>
<br>

On the ```Anonymous access level```, select ```Container(anonymous read access for containers and blobs)``` then click ```Ok```.

<img width="993" height="277" alt="2026-04-26_19-55" src="https://github.com/user-attachments/assets/30ffa37a-b757-42bf-909e-88acbe953145" />
<br>
<br>

To verify the changes, the ```Anonymous access level``` status should be set as ```Container```.

<img width="594" height="86" alt="2026-04-26_19-58" src="https://github.com/user-attachments/assets/52b3debf-6fb4-47db-baf0-d62fcfcdd190" />
<br>
<br>
