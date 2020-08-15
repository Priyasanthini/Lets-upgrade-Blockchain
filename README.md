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
}
Transaction Hash:0x95a29f27abc22d7d402d08f21976d5b8c40ee58c903e3b2ad2a33d51d63c5b23
From: 0xfa1177e3cb219b2e5bc0c66cfc0d780f0ae00ff9
TO: 0xdb280ccc84a86777ac324eb6cc2b0c379031c9b2
CONTRACT ADDRESS : 0xFA1177E3CB219B2e5bC0c66CFC0D780f0aE00Ff9
ROPSTEN WEBPAGE : https://rinkeby.etherscan.io/tx/0x95a29f27abc22d7d402d08f21976d5b8c40ee58c903e3b2ad2a33d51d63c5b23
