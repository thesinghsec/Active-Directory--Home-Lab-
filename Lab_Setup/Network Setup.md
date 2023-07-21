# Creating network

Whole in Virtual Box, hold ctrl+h to launch 'Network Manager'. Alternatively, click on **File > Tools > Network Manager**.

![image](https://github.com/thesinghsec/Active-Directory--Home-Lab-/assets/126919241/77e61f7a-aff4-4ab0-98e5-38432ce5bfc0)

Then Click on the "NAT Networks" tab.

To create the "external" network, click on the green icon with the "+" sign.

    Name: External
    CIDR: 192.168.3.0/24
    Enable the network by checking the checkbox.

Repeat the same process to create the "internal" network:

    Name: Internal
    CIDR: 192.168.16.0/24
    Enable the network by checking the checkbox.

Finally, create the "secure" network:

    Name: Secure
    CIDR: 192.168.116.0/24
    Enable the network by checking the checkbox.
    
![image](https://github.com/thesinghsec/Active-Directory--Home-Lab-/assets/126919241/7688be12-0220-4c86-b4a1-0f2dc3598bd1)

