## zrem ##

**Interface:** `/zrem`

**Method:** `GET | POST`

**Parameter:** 

*  **tb** (Required)  
*  **key** (Required)  
*  **ver** (Optional)

This interface is a proxy interface for `/hustdb/zrem`. See more details in [here](../hustdb/hustdb/zrem.md).  

**Sample:**

    curl -i -X POST "http://localhost:8082/zrem?tb=test_table" -d "test_key"

[Previous](../ha.md)

[Home](../../index.md)