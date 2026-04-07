## Create and Configure Network Security Group (NSG)

On this demo, we will create a Network Security Group(NSG) in azure. On the Azure Dashboard, go to the search and type ```NSG``` then click the ```Network security groups```.

<img width="524" height="234" alt="2026-04-07_18-38" src="https://github.com/user-attachments/assets/a17c75fb-5d42-4630-abfd-4d71de64a4dc" />
<br>
<br>

Click ```Create```.

<img width="624" height="294" alt="2026-04-07_18-40" src="https://github.com/user-attachments/assets/448b8101-a060-4a55-8c36-9fc34bedffc2" />
<br>
<br>

We will then name it as ```datacenter-nsg``` then click on ```Review + create```.

<img width="805" height="881" alt="2026-04-07_18-42" src="https://github.com/user-attachments/assets/7e9e1a54-e9ea-4f6a-8670-9bd3ca5a3b7e" />
<br>
<br>

## Create Inbound Security Rule

Under Settings, click on ```Inbound security rules```.

<img width="289" height="421" alt="2026-04-07_18-44" src="https://github.com/user-attachments/assets/7ef0a47b-7691-4e27-b3da-4aa9ba7ad6bb" />
<br>
<br>

We will then need to create and add an inbound rule named ```Allow-HTTP``` for ```HTTP``` service on port ```80```, with the source range of ```0.0.0.0/0```.

<img width="575" height="907" alt="2026-04-07_18-47" src="https://github.com/user-attachments/assets/5d847d9e-7920-403e-b1d7-77e723fc9d7a" />
<br>
<br>

Add another inbound security rule named ```Allow-SSH``` for ```SSH``` service on port ```22```, with the source range of ```0.0.0.0/0```.

<img width="562" height="915" alt="2026-04-07_18-51" src="https://github.com/user-attachments/assets/f0f9f9d3-6587-48cc-aa3e-50fc5f6eb1ce" />
<br>
<br>












