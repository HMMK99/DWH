Data Warehouse
    Data Model
        - Organize Data Elements.
        - Descripes entities, constraints, data structures and objects.
        - Formalizes relationships and how the report got regulated from DWH.
        - Descripes bussiness logic.
        - not a : science but engineering practice, static, database type, new invention.
        - a : general concept for full architicture, different based on use case and DB type, customizable, affect reporting performance.
        - First part before new system integration.
        - Connection layer between bussiness and technical, Logical and physical also.
        - unified accross all system with same patterns and practices.
        - Engaged in early stages.
        - Output is model design and mapping sheet.
        Design Vs Implementation
            - Requrments D
            - Architict to transform them to design D
            - I is the most important
        Elements Of Data Model
            - Facts
                info we need to extract depend on measurements (calls, transactions,...etc) per dimention
            - Dimentions
                more info about the fact like customer or emplyee table
                context around bussiness process event
            - Attributes
                characteristics in the dimentions


            * Fact table
                the primary table in dimentional model located in center of star or snowflake schema
                PK and FKs and AGGs
            * Dimention table
                referance data, lookup data, profile
                PK
        
        Life Cycle
            - Gathering requirements
            - Identify granuality of the facts meaning total number of calls per hour/day/month...etc
            - Identify dimentions and facts
        
        Dimention types
            - Conformed - Degenerate    - Junk  - role playing - Snowflake  - Slowly changing dimentions .........etc