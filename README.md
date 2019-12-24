# knowledge_graph2recommandation_system_tutorial
This project is a tutorial about how to build knowledge graph(KG) and how to establish recommendation system RS based KG  
It will include below parts:
- According to your data/bussiness/plan, how to bulid up schema
- How to gather row data 
- How to extract knowledge
- How to build up 'triple' head relation tail
- How to store knowledge
- How to learning knowledge: including based on distance/based on semantic/NN
- How to apply embedding knowledge to recommendation system 

# KG strctures
Generally, KG data is triple: entity-relation-entity, sometimes we also call entity as topic, like Trump.  
Relation can be divided to 2 part: property and relation. The difference is **property** usually links same entity, like **Trump-gender-male**  
**Relation** links two different topics, like **Trump-president_of-US**

# how to bulid up schema
Schema is one of the most important parts of your whole project/bussiness, cuz first you have to work out what you are planning to do based on KG and RS. Be familiar with your/your client's needings, then you start to establish schema. Maybe you have lots of row data, but you only need some parts or maybe it is still not enough.   
For example, you are the boss of certain brands, you wanna make KG and RS for people who subsribe memberships. Then you may choose properties of membership: membership_id, gender, age, program_name, organization_name...; Properties of things: discount, original price, category, season...
