# JMeter Listener For Microsoft Azure CosmosDB
  This is an abstract listener for JMeter to push the result to Azure Cosmos DB, with this listner you can push the JMeter runtime result to Azure Cosmos DB.

---
  ## Contributing
  ### Step 1
  - **Option 1**
      - 🍴 Fork this repo!
  - **Option 2**
      - 👯 Clone this repo to your local machine.
  ### Step 2
  - **HACK AWAY!** 🔨🔨🔨
  ### Step 3
  - 🔃 Create a new pull request.
---  

### Pre-requisits
* Azure Account with Cosmos DB configured with a partition key.
* Jmeter 3.1 or above (** Crypto-js libraries for generating the auth token for connecting to cosmosdb)
* Basic groovy scripting



### Set up steps
* Step 1: Azure Cosmos DB set up & configuration
  * Get the primary key and URI for Cosmos DB
    [![Cosmos.png](https://i.postimg.cc/JhrQXzMH/Cosmos.png)](https://postimg.cc/CR2DTYZw)
* Step 2: Jmeter Configuration
  * Download JMeter
  * Download and extract the crypto-js (_[can be download from here](https://github.com/brix/crypto-js/releases)_) library to __jmeter/bin__ folder
* Step 3: Sample thread plan attached.
  * Configure the auth token generator for cosmos db.
 
    [![Auth-Token-Generator.png](https://i.postimg.cc/J41JP4s1/Auth-Token-Generator.png)](https://postimg.cc/PNRPqHbc)
  * Listner for writing to the Cosmos DB.
 
    [![Listner.png](https://i.postimg.cc/d1YD34dq/Listner.png)](https://postimg.cc/yJL7rhv5)
    
    
 ### Team

> Or Contributors/People

| <a href="https://www.linkedin.com/in/jyoti-prakash-mallick-10488b1b/" target="_blank">**Profile**</a> |  
| :---: |  
| [![Passport-Photograph.jpg](https://i.postimg.cc/prCNWtr6/Passport-Photograph.jpg)](https://postimg.cc/p5mcC4Df)    |  
| <a href="https://github.com/JyotiPrakashMallick/Jmeter-Listener-CosmosDB" target="_blank">`github.com/JyotiPrakashMallick/Jmeter-Listener-CosmosDB`</a> |
