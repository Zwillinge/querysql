JSON to SQL Query
==================

Converts JSON config to SQL Query

```json
{
  "glue": "and",
  "rules": [{
    "field":"age",
    "condition":{
      "rule": "less",
      "value": 42
    } 
  },{
    "field":"region",
    "includes": [1,2,6]
  }] 
}
```

