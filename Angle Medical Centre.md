s# Group 3
## Angle Medical Centre Network Progect

## Summary


## Scope/Objectives

  1. Define department and subnets
  2. Establish Network Infrastructure test on the Packet Tracer
  3. Devices List and port connect
  4. Configure devices command
  5. 
## Step 1. Department 


| Department      | Number      | Network          |Vlan          |Gateway       |
| -------------   | ------------- | -------------- |------------- |------------- |
|Medical          | 28            |192.168.10.0 /24|10            |192.168.10.1
|GeneralServices  | 10            |192.168.20.0 /24|20            |192.168.20.1
|Lab              | 4             |192.168.30.0 /24|30            |192.168.30.1
| Frontdesk       | 3             |192.168.40.0 /24|40            |192.168.40.1
| Marketing       | 3             |192.168.50.0 /24|50            |192.168.50.1
|Admin            | 3             |192.168.60.0 /24|60            |192.168.60.1
|Pharmacy         | 3             |192.168.70.0 /24|70            |192.168.70.1
| IT              | 3             |192.168.80.0 /24|80            |192.168.80.1
| Management      | 1             |192.168.90.0 /24|90            |192.168.90.1




## Step 2. Establish Network Infrastructure test on the Packet Tracer

![67dde0c19f3e87773f4ee1ea9510a45](https://github.com/user-attachments/assets/3390897d-926e-43c8-ac45-9d8b68b832da)


### 2.1 Devices List

| Device name      | Version     | Numbers
| ------------- | ------------- | ------------- 
|Layer3 Switch | 3560-24PS|2|
|Switche| 2960-24TT Switch2|3|
|Server| Server-PT|3|
|Wireless Router| HomeRouter-PT-AC|1|
|Laptop| NA|7|
|Workstation| NA|14|


| Device        | Name     | Network        |Gateway        |IP Adress  |
| ------------- | ---------| -------------  | ------------- | ------------- |
| Layer3 Switch |  MLS-1   |192.168.1.0    |192.168.1.1  |192.168.1.2


## step 3.  Console Connections for Devices

## **Connections Between Switches and Multi-layer Switches**
- **MLS-1 F0/1** ----- **S-2 F0/23**  
- **MLS-1 G0/2** ----- **S-3 G0/23**  
- **S-1 FE0/1** ----- **S-2 FE0/1**  
- **S-1 FE0/2** ----- **S-2 FE0/2**  

## **Connections Between Multi-layer Switches and Other Devices**
- **S-2 FE0/23** ----- **MLS-1 FE0/2**  
- **S-2 FE0/24** ----- **MLS-2 FE0/1**  

## **Connections Between Switches**
- **S-2 FE0/3** ----- **S-3 FE0/3**  
- **S-2 FE0/4** ----- **S-3 FE0/4**  

## **Connections Between Switches and Routers**
- **S-2 FE0/5** ----- **WR-1 0/1**  
- **S-3 FE0/5** ----- **WR-2 0/1**  

## **Connections Between Switches and Servers**
- **ServerFile F0** ----- **Fa0/10**  
- **ServerDHCP F0** ----- **Fa0/11**  
![image](https://github.com/user-attachments/assets/7c94c010-5685-44e5-bd33-4a9edbdbd1b0)





