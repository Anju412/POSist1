# POSist1

#include <iostream>
#include <string.h>

int main()
{
struct genesisNode
{
  string data;
  string nodeId;
  string referenceNodeId;
  string childReferenceNodeId[10];
  string genesisReferenceNodeId;
  string hashValue;
  int nodeNumber;
};

struct *a=structNode* (malloc(sizeof(genesisNode)));
a=NULL;
cout<<"Enter Node Number";
cin<<nodeNumber;
cout<"Enter nodeId";
cin<<nodeId;
cout<<"Enter Reference NodeId";
cin<<referenceNodeId;
cout<<"Enter Child Reference NodeId";
cin<<childReferenceNodeId;
cout<<"Genesis ReferenceNodeId";
cin<<genesisReferenceNodeId;



