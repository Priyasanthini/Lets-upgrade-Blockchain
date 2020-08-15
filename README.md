


question number: 14
SMART CONTRACT CODE:
pragma solidity ^0.4.17;

 contract train{
    
    string public  name;
    string public trainname;
    string public departure;
    uint public timimg;
    int public cost;
    
    
    function trains (string newname , string newtrainname , string newdeparture , uint newtimimg , int newcost )public{
        name=newname;
        trainname=newtrainname;
        departure=newdeparture;
        timimg=newtimimg;
        cost=newcost;
        
        
    }
    
    function SetDetailspublic(string newname , string newtrainname , string newdeparture , uint newtimimg , int newcost )public{
        name=newname;
        trainname=newtrainname;
        departure=newdeparture;
        timimg=newtimimg;
        cost=newcost;
    }
    
    function  getDetails()public view returns(string,string,string,uint,int){
        return(name,trainname,departure,timimg,cost);
    }
}
Transaction Hash:0xe43cf5d6fb875683636ef0f69e8d96f8f76254d0fd00f8990a9becdbe4e40991
From:0xfa1177e3cb219b2e5bc0c66cfc0d780f0ae00ff9
TO: 0xa20e30b6a42107f8b182c5cc71770c71db73efe4
CONTRACT ADDRESS :0xFA1177E3CB219B2e5bC0c66CFC0D780f0aE00Ff9
ROPSTEN WEBPAGE : https://rinkeby.etherscan.io/address/0xfa1177e3cb219b2e5bc0c66cfc0d780f0ae00ff9




question number : 22 
SMART CONTRACT CODE : 
pragma solidity ^0.4.17;

contract employee{

string public empname;
int public empid;
int public salary;


function employees (string newempname , int newempid , int newsalary )public{
    empname=newempname;
    empid=newempid;
    salary=newsalary;
    
}

function SetDetails(string newempname , int newempid , int newsalary )public{
    empname=newempname;
    empid=newempid;
    salary=newsalary;
}

function  getDetails()public view returns(string,int,int){
    return(empname,empid,salary);
}
} Transaction Hash:0x95a29f27abc22d7d402d08f21976d5b8c40ee58c903e3b2ad2a33d51d63c5b23
From: 0xfa1177e3cb219b2e5bc0c66cfc0d780f0ae00ff9 
TO: 0xdb280ccc84a86777ac324eb6cc2b0c379031c9b2
CONTRACT ADDRESS : 0xFA1177E3CB219B2e5bC0c66CFC0D780f0aE00Ff9 
ROPSTEN WEBPAGE : https://rinkeby.etherscan.io/tx/0x95a29f27abc22d7d402d08f21976d5b8c40ee58c903e3b2ad2a33d51d63c5b23
