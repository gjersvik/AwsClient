awsdart
----------
Awsdart is a library to make it easier to use Amazone Web Service API in dart.

WARNING this package is very new and unstable. Do not use for anyting important. But please test and give feedback. WARNING

The main goals for the project.

* Layered implementation.
* Documented.
* Well tested.

###Layers
**Layer 0:**
This layer only do signing of requests with your amazon credential. And simple checksum validation of the response. So you can use it to implement any aws api.  
**Layer 1:** 
Is a one to one mapping of the aws api in dart.  
**Layer 2:**
A more dart natural api based on layer 1 apis.  

###Project Status.
* **Layer 0:**
    * Signing request. [Beta] A lot of unit test. 

[ ![Codeship Status for gjersvik/AmazonDart](https://www.codeship.io/projects/0e6905e0-9305-0131-1c79-0ef75c22b34f/status?branch=master)](https://www.codeship.io/projects/16595)

_This project is licensed under the BSD 2-Clause License._
