# Lets-upgrade-Blockchain
solidity code for smart contract on report card.sol

CODE AS FOLLOWS: 
pragma solidity ^0.4.17;

contract report{
    
    string public StudentName;
    int public RegisterNumber;
    int public BatchNo;
    int public DataStructure;
    int public java;
    int public ComputerVision;
    int public ArtificialIntelligence;
    string public Status;
    
    function reports(string newStudentName, int newRegisterNumber,int newBatchNo, int newDataStructure, int newjava, int newComputervision, int newArtificialIntelligance,string newStatus) public{
        
        StudentName = newStudentName;
        RegisterNumber = newRegisterNumber;
        BatchNo = newBatchNo;
        DataStructure = newDataStructure;
        java = newjava;
        ComputerVision = newComputervision;
        ArtificialIntelligence = newArtificialIntelligance;
         Status = newStatus;
}
    function SetDetails(string newStudentName, int newRegisterNumber,int newBatchNo, int newDataStructure, int newjava, int newComputervision, int newArtificialIntelligance,string newStatus) public{
        
        StudentName = newStudentName;
        RegisterNumber = newRegisterNumber;
        BatchNo = newBatchNo;
        DataStructure = newDataStructure;
        java = newjava;
        ComputerVision = newComputervision;
        ArtificialIntelligence = newArtificialIntelligance;
        Status = newStatus;
}

   function  getDetails()public view returns(string,int,int,int,int,int,int,string){
   return(StudentName,RegisterNumber,BatchNo,DataStructure,java,ComputerVision,ArtificialIntelligence,Status);
}

}

        
TRANSACTION HASH : 0xbf1fa3ecd20b953c045494b0265ce4bbec2308a102af6d05b88add5cf27cbe33
FROM : 0xfa1177e3cb219b2e5bc0c66cfc0d780f0ae00ff9
TO : 0xa06ad5d98701a687408d0d2f4253ecbe54682f2a

Test Deployment of the Smart Contract can be found in 0xa06Ad5D98701a687408D0D2F4253eCbe54682f2A in
https://rinkeby.etherscan.io/address/0xa06ad5d98701a687408d0d2f4253ecbe54682f2a
