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
                            - What Is OEE? OEE (Overall Equipment Effectiveness) is a “best practices” metric that identifies the percentage of planned production time that is truly productive. An OEE score of 100% represents perfect production: manufacturing only good parts, as fast as possible, with no downtime.

- **OPC UA Companion Specifications defines the form in which machine provides certain informations**, which makes
    - **integrating** the machines into an existing production environment
    - and **configuring** the machines much easy
        - which in turn makes enginners' work, much more efficient
        - That's how Industry 4.0 works


- Thus, we see that OPC UA generates data and it is in form of huge graphs.
- This gives a huge opportunity to data analytics like our author.
- This brings us to our next question, **Objectives**
- In order to query this huge graph, there is a non publicly available query language for OPC UA, which is flawed.
- Through this paper, the author would attempt 
    - to query OPC UA graphs through SparQl
    - setup rules to transform OPC UA queries to SparQl
    - point out the flaws in OPC UA Query
    - Bypass the flaws through SparQl

- Now, how did the author come to the conclusion of using SpaarQl? That was indeed the research question to choose the right query language out of Cypher, Gremlin, GraphQl and SpaQl