# Blockchain_crowdfunding

This project is made for the Blockchain club in IIT Madras.
I have used solidity for deploying this code and the payable options for the customers and the manager.
I havent made the deploy button as private as within the constructor itself I have given a condition for the msg.sender to be a manager(owner of deployment)
Therefoer the minimum contribution and the target value are to be set by the manager.
The deadline is already fixed as 2 days.
You can give the minimum contribution as wei which is the smallest combo of ether.
In solidity in the payable option itself it is enabled for the people to transact in ether.
So all comditions for the project are met.Even the approval of each request is taken care using the acceptRequest Function.
