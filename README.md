# 30-days-of-azure
My main goal is that i should prepare myself for Az-900 exam and learn the basics of cloud computing
 
#  DAY 1 of azure 
 
# Introduction to cloud computing
 
 means the delivery of services over internet.If we need to increaes our   IT infrastructure we increase without even waiting to build new data centre.We can use cloud to rapidly expand our infrastructure. 
  
  Common services are:
  
     * virtual machine(vm)
     * storange 
     * data bases
     * networking
   Tradition services are:
   
       * IOT
       * Artificial Intellgence(AI)
       * Machine Learning(ML)
  
  
 
# The basic service provided by all providers are 
 1) compute power
 
 Compute power means how much processing our computer/system can do .
  Example :- If we have bought a computer with some storage capacity.Our  system will become slow as load on our system increases.So if we use cloud computing by which we can add or remove computing power based on our choice . In cloud computing we are only paying for services what we use.

2) storage power
 
 Storage power means how much volume of data we can stone in our system.
 
 Eg:- Normally the systems are with limited storage space in our system .As year passes we require more space in our system so for this we can't change system or upgrade
 instead of that we can use cloud computing . For which we just need to request for more storage from cloud  provider. Cloud computing makes the back up our system and keeps our Os Updated.
 
 # DAY 2 OF AZURE
 OVER VIEW OF AZURE :-
 
    *Compute
    *Storage
    *Networking 
    *Migration
    *Devops
    *IOT
    *Analytics
    *AI
    *INTEGRATION
 
 For most application we need 3 core resources:-
 
     * Compute
     * Storage
     * Networking
 
  
 # 1) Compute;-

   i) Virtual Machine:- Azure VM are known as  IAAS(Infrastructure as a serivce).
      Eg;- If we are running an application on  on-premisi infrastructure we can move it to azure by Lift and Shift.
 
   ii)Azure app service
   
    * This is an PAAS(PLATFORM AS A SERVICE)
    * It lets us host web and applicatin without having worry  about the underlying infracture.
    * Sometimes we even us Vm when they are not web or mobile application
   
 iii) Azure Container instace
 
     *This are self containde software environment.
     *Container are like Vm except they don't contain Operating system.So it's weight is less than Vm so it's easiest way to deploy .
     *Container they run on Vm.
  
  iv) Azure Kubernetes services:-
  
    * It is known are Container Orchestrator.
    * It make easy to deploy multiple containers together
  
  v) Azure function 
  
    * it is microsoft main serverless offering
    * it is like azure app service
    * It executes the individual function rather than entire application .In this we only when the azure function is running.
 
  # 2) STORAGE
  
  ## i)Blob storage:- 
     
     * it is the simplest storage .It does not having hierarchcal folder structure.
     * it contain unstructured data like photos, video , log files.
     
     It has multiple access tier's 
      i) Hot :- fresqtly acdess
      ii cold :- infrastructure access
      iii) Archieve;- rarely accessed.
      
      
   ## ii) Azure file store  
      * They are used for stuctured file storage(hierarchical file storage)
      
   ##  iii) Azure data lake storage gen2
       * They are use for stuctured file storage(hierarchical file storage).
 # DAY 3 OF Azure  
   ## RELATIONAL DATABASES
    i) Azure sql databases
    2) Azure db for mysql
    3) Azure  db for maria db
    4) azure db for postresql
     
   ## NO SQL database
    1) Azure cosmos db
    2) Azure cache for reddis
    
  # NETWORK
  #### i) VNET
  * The VM are connected together in a group to form a vnet  . 
  * A virtual network is similar to On- premises network . 
  * Each vm in a vnet get a Ip address so that they can communicate to other vm.
  #### ii) subnet 
  * We can divide the vnet into subnet and defines routes how the traffic should flow between them .
  * By default all the outbound traffic is from VM to internet is allowed.
  *  For inbound traffic we need to assign public Ip address to Vm.
  #### iii) Vnet Peering
  *If we want VM of one vnet to communicate to vm of another vnet we can do using vnet peering.
  #### iv) VPN(VIRTUAL PRIVATE NETWORK)
  * If we want a secure connection between Vnet and On-premises network we can use Virtual private network.
  * VPN:it sends encypted traffic over the public internet.
 #### v) Express Route
 * It is expensive than VPN.
 * There is dedicated connection between Vnet and On-premises , high Speed and reliable.
 
