# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP:
![2c](https://github.com/MANISHA21SS/2c.ARP_RARP_PROTOCOLS/assets/147474298/e6c1f40c-e23e-48be-9943-790f851a8383)

## OUPUT - ARP:
![2c client out](https://github.com/MANISHA21SS/2c.ARP_RARP_PROTOCOLS/assets/147474298/1535573c-0a7d-4beb-9bb6-bdac9c9f5347)

## PROGRAM - RARP:
![2c server](https://github.com/MANISHA21SS/2c.ARP_RARP_PROTOCOLS/assets/147474298/3243d86f-b4da-483f-b785-171eae3e566d)

## OUPUT -RARP:
![2c server out](https://github.com/MANISHA21SS/2c.ARP_RARP_PROTOCOLS/assets/147474298/d5eaa5fd-3eb4-425c-ba23-2d564cfe21fe)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
