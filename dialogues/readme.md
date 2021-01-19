- OPC UA allows engineers               
    - a platform independent
    - interoperable
    - and vendor independent integration of 
        - different machines in production

- VDMA represents 
    - more than 3200 member companies 
    - and is the voice of the mechanical engineering industry in Europe

- VDMA supports manufacturers in developing
    - OPC UA companion specifications like 
        - platform independence
        - interoperability
        - vendor independence 
    which ensures 
        - smooth Industry 4.0 communications
        - Industry 4.0 communications is ensured between 
            - both machines and 
            - from machines 
                - to other systems
                    - which leads to more efficient production.
                    - For engineers, this results in the Industry 4.0 application fields
                        - of plug and play/work
                        - condition monitoring
                        - predictive maintainence 
                        - and OEE improvements.
                            

- **OPC UA Companion Specifications defines the form in which machine provides certain informations**, which makes
    - **integrating** the machines into an existing production environment
    - and **configuring** the machines much easy
        - which in turn makes enginners' work, much more efficient
        - That's how Industry 4.0 works


- Thus, we see that OPC UA generates data and it is in form of huge graphs.
- This gives a huge opportunity to data analytics like our author.
- This brings us to our next question, **Objectives**.
- The main objective is to put in place an **efficient** way of querying this huge graph.
- There could be a 1000 devices connected to a OPC server in one factory. On attempting to connect another factory, there would be another thousands of interoperable devices making this a huge graph.
- In order to query this huge graph, there is already an existent non publicly available query language for OPC UA, which is flawed.
- Through this paper, the author would attempt 
    - to query OPC UA graphs through SparQl
    - setup rules to transform OPC UA queries to SparQl
    - point out the flaws in OPC UA Query
    - Bypass the flaws through SparQl

- So, it is clear that OPC UA produces huge connected graphs
- So, naturally the question arrises to test the capability of OPC UA query system to find out if it is capable to query such huge connected graphs.
- There are flaws in the OPC UA query system.
- The concepts used in the OPC UA query system, can those be replaced by OWL? How can OWL be integrated into the automation standard of OPC UA?
- Now, if we have to replace the OPC UA query system, altogether, what would be our best option out of the following?
- We have to take care of the fact that the chosen query language 

- Now, how did the author come to the conclusion of using SparQl? That was indeed the research question to choose the right query language out of Cypher, Gremlin, GraphQl and SparQl..

How can smart services be integrated into the future organisational architecture?

How can Owl be integrated into the automation standard OPC UA

OPC UA query system capable to query such large connected graph