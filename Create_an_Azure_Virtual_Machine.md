## Create an Azure Virtual Machine

On the search bar, type **Virtual Machines** then select the first service that appears.

<img width="523" height="165" alt="2026-01-10_08-30" src="https://github.com/user-attachments/assets/5fc38f00-8b30-4a6d-bc66-415f758b94f5" />
<br>

Under the **Virtual Machines** Section, click **Create> Presets**.

<img width="1145" height="655" alt="2026-01-10_08-45" src="https://github.com/user-attachments/assets/1193642c-7475-450b-b449-401a60ed9d2e" />
<br>

On the lower-left corner, click on **Skip this step.**

<img width="322" height="82" alt="image" src="https://github.com/user-attachments/assets/585bfbfc-3c13-423d-b859-14ee5c415c49" />
<br>

Next, we will then need to follow the requirements for this demo:

1) Use the existing resource group.

2) The VM name must be ```nautilus-vm```, it should be in ```West US``` region.

3) Use the ```Ubuntu 22.04 LTS``` image for the VM.

4) The VM size must be ```Standard_B1s```.

<img width="727" height="780" alt="2026-01-10_09-08" src="https://github.com/user-attachments/assets/b7278260-1631-4f11-aace-149f169b0841" />
<br>

5) Attach a default Network Security Group (NSG) that allows inbound SSH (port 22).

<img width="699" height="205" alt="2026-01-10_08-59" src="https://github.com/user-attachments/assets/5ae35a33-74f1-4800-8a11-81eba5bdb7ef" />
<br>

6) Attach a 30 GB storage disk of type ```Standard HDD```.

7) The rest of the configurations should remain as default. Once done, click on **Review + create**

<img width="728" height="906" alt="2026-01-10_09-02" src="https://github.com/user-attachments/assets/8e9a6224-c217-469c-9248-31afa9cdeef1" />
<br>

8) Click on **Create**.

<img width="747" height="893" alt="2026-01-10_09-05" src="https://github.com/user-attachments/assets/ac370410-9148-407e-b9c0-a51aaf5bd1a8" />
<br>

9) Click on **Download private Key and create resource**.

<img width="316" height="206" alt="image" src="https://github.com/user-attachments/assets/07af26c8-179a-4b8e-844a-d7bb5b398df6" />
<br>
