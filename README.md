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
    
  # NETWORKING
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
 # DAY 4 OF AZURE FUNDAMENTALS
# Azure Services
 ## 1) Migration
#### i) Azure migrate
 * It discovers your On-premises server   both physical and virtual.
 * It assess (evaluates) these machines.
 * Form each one it tells 
   i) Whether or not it's ready to migrate .
   II) How big the azure vm should be.
   III) How much it will cost.l
   IV) Any dependent server that will also need to be migrated.if it's ready then it will help you in the migration.
 * Azure migrate will integrate with other tools like sql, server,web apps to migrate.

#### ii) Azure active directory
 * It manges the identities that take care of authentication.
 *  There are many option for synchronizing On-premisis active directory to azure active directory.
 
 # 2) DEVOPS
 * using devops we can automate the building,testing and relesing of application update.
 
 ### i) Azure pipeline
 * It is the most important service.
 * Using azure pipeline we can create the automated workflow to continously build, test and deploy code.
 ### ii) Azure Devtest Labs
 * It gives some extra capabilites  for eg it allows the admin to control the cost by setting a limit how many Vm's can be deployed at once and ensuring that Vm should shout down when they are not in use.
### iii) Azure CDN(Content Delivery Network)
* It is used for speeding the responsiveness of our application.
* It helps to take advantage of microsoft extensive networks.
* It caches the most frequently accessed content from the location around the world so that your  end user can retrive the content from the closest point from network which helps in making your web application  feels like local network.
# DAY5 OF AZURE FUNDAMENTALS

# 3) Azure IOT
  * Microsoft offers a suite of services to organisations to connect, monitor and control IOT devices using 
   # i) Azure IOT central:- 
    * Which is fully managed Software-as-a-service(Saas) solution.
    * It  let's us create IOT application without writing any code.
   # ii) Azure IOT hub
   * If we need to create more customized applications then we can use azure IOT hub.
   * It handles secure communication for IOT devices.
   * IOT central uses IOT hub behind it's scene.
   # iii) Azure sphere
    
    * We can use Azure sphere to make our IOT devices more secure.
    * it includes
       * Certified chips 
       * Azure sphere OS
       * Azure spher cloud security
       they provide layers of protection to our IOT devices.
 # 4) Analytics
   * Apache Spark is the king 
 ### i) Azure HDinsight:- 
 
   * It supports open source big data frame works such as
      * Hadoop 
      * Spark
      * Hive
      * Storm
 ### ii) Azure Databricks :-
  * It runs similar to HDinsight because it support Spark and it's more user friendly and easier to manage.
 
 ### iii) Azure Synapse Analytics;- 
  * It's new version of Azure SQL DataWare House functionality  and  it also supports Spark.
 # DAY O6 OF AZURE FUNDAMENTALS
# 5) Artifical Intelligence
 * Here we feed lots of real world data in programs and programs maek generlization about the data this is  known as training a model . When it's give new data it uses this generlizations.
  Eg:- Netflix gives recommentdation of movies to us using this generlization.
  services
## i) Azure conginitivee Service
 * It consist of pre-built AI tools . 
 * We can add AI  capabilities to the Application evenif we don't know thing about AI.
    Types of Azure conitive service 
    i) Decision 
    ii) Language 
    iii) Speech 
    iv) Vision 
    v) WebSearch
    Here vision category includes vision API which can classify images and face API  which can detect faces in images.
 ### ii) Azure Bot SErvice 
  * It gives tool to create chat bot which is an intelligent  chatbot 
  * Which can handle simple support request for customers.
 ### iii) Azure Machine Learning Studio
 * If we have basic knowledge of ML then we can try ML studio.
 * Which lets us train and deploy models without coding using drag and drop.
 ### iv) Azure ML Service 
 * It gives full control of ML service like train, Packages, monitor ,deploy, validate.
 * we can use python based  framework such as tensor flow or pytorch.
 * Train model using Azure Databricks 
 * Deploy Azure kubernetes Service.
 * It is the best solution when you need to build own customer AI application.
### v) Integration
For eg;- If we are using Blob storage and we are storing something in Blob storage and we need the notifications when the documents arrive we use Azure logic apps 
to to automate this kind of task using drag and drop.
* We also use event grid to notify the azure logic app for event occurance.
# DAY 07 OF AZURE FUNDAMENTALS
# MANAGING SERVICES
## i) Azure Monitor :- 
   * It is used to track what's happening with your azure resources.
   * azure monitor is collection of monitoring tools.
   * Core features of monitor are 
    i) Matrix
    ii) Alerts
  #### i) Matrix :-
   *  It's statistic on aspects like resources such as CPU used on Vm and space used on Blob storage.
   *   Azure monitors creates a graphs showing how this matrix have changed over time.
   *   It can also used to watch critical matrix which we specify and send us the alert if their is any problem.
  #### ii) Alert
  * Here we Create alert for planned and unplanned outages.
  ## ii) Azure Backup
  * It's always a good idea to have a back up of services this helps to recover from service failures.
  * Most azure services they have their own built in back up capabilities like Cosmos DB.
  * Here Azure vm are different from Cosmos DB because we back then using Azure Backup .
  * We can also use this service to back up our On-premises System.
  ## iii) Azure Advisor
  * It will us how to improve the Performance and availability of our application and how to reduce cost.
  *  Eg:- If azure advisor finds any unutilized VM then it us suggests to use smaller VM and less costly VM to perform same task.
  *  Azure advisor it also provides Security Recommandation .
  *  Azure advisor gets security recommandation from Microsoft defender for cloud.
  ## iv) Microsoft Defender for Cloud
  * It is formerly known as Azure security Center.
  * It gather security Information from resource across our subscription and access our vulnerability.
  ## v) Azure policy
  * We can create our own custom policies from scratch .
  ## vi) ARM (AZURE RESOURCE MANAGER) TEMPLATE
  * When we create ARM template it specifies configuration details for one or more resources.
  ## vii) Azure Blue Print
  * It lets us Automate the entire deployment environment.
  * It is a collection Arm template with few details like policy,user permission.
  * When blue print is assigned to subsription it not only automate the creation of environment but also keeps the record of deployment.
  
# DAY 08 OF AZURE FUNDAMENTALS
 #Azure Virutuel Machine Availability and Scalabilty
 * Virtual machine have gone from revlutionary to being a standard part of every organization infrastructure but now containers are revoutionary technology.
 * VM it gives full control over the 
   i) Software
   ii) Operating System 
   Which we want to run. 
 # High Availability
 * high availability :- An application it will continue to run in case hardware failure or event causes system to go down .
   # Services to help with high availability 
   ## i) Availability Set 
    * A group of VM that can handle planned and unplanned down time. 
 ### 1) Planned downtime
  * Azure updates infrastructure underlying and reboots the VM 
 ### 2) UnPlanned downtime
  * When VM goes down Unexpectedly when it has hardware failure.
### To handle planned downtime 
  ### Availability Set Groups :- 
  * It uses Update domain.
  * Azure perform planned maintenance, it Updates one domain at a time .
  * so that VM of one domain is being rebooted while VM of another update domain keeps running.
  * We can configure upto 20 update domain in a avialability set.
 ### To handle unplanned downtime:- 
  * It is also handled in a similar way but we will use fault domain.
  * Each fault domain have separate power source and network switch.
  * It limits the downtime caused by hardware failure.
  * Eg:- If there is power failure in one fault domain it does not affect the VM running in other fault domain.
  * Maximum we can have 2 or 3 fault domain based on our region.
  * Each Vm is int both update domain and fault domain.
  * For 99.95% of Uptime guarantees  you must have atleast 2 VM,2 update domains, 2 fault domain . 
 
    
