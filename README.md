# css-ia1
Python-nmap implementation for CSS IA1

# About

We have compared using sockets and python-nmap library for scanning various ports. 


Sockets method allows us to check which ports on an address are open. Although, it does not provide any other information about those ports which are closed.


To overcome this, we used the python-nmap library. This allows us to see more detailed information on a range of ports selected on a particular address such as open, closed, filtered etc.


# How to run


Clone the project to your local machine


Download nmap from [here](https://nmap.org/download.html)


Then in cmd:
```
pip install python-nmap
```


Move to the folder where you have cloned the python files


Run ``` python3 portscan-sockets.py ``` file for using sockets method


Run ``` python2 portscan-nmap.py``` for using nmap method

All comments have been mentioned in the scripts for better understanding of the implementation.


# Screenshots
### Using sockets
<img width="623" alt="port scanner using sockets" src="https://user-images.githubusercontent.com/66993183/154523234-3703574c-5edd-4c9f-81e0-213929529d7e.PNG">


### Using nmap
<img width="629" alt="port scanner using nmap" src="https://user-images.githubusercontent.com/66993183/154523257-05907066-0ce5-4487-aa6f-d6b84d70f391.PNG">
<img width="611" alt="port scanner using nmap2" src="https://user-images.githubusercontent.com/66993183/154523277-59a922e7-18d1-4727-833c-33f2d766910b.PNG">


# Team members


[Pranav Patki 1911038](https://github.com/pranav0609)


[Divyam Patani 1911035](https://github.com/divyampatani)


[Raj Rathod 1911043](https://github.com/ArerehRaj)
