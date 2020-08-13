## Access-the-nested-key-salary-from-the-following-JSON
## Sample code to check nested key salary
```sh
import json

sampleJson = """{ 
   "company":{ 
      "employee":{ 
         "name":"emma",
         "payble":{ 
            "salary":7000,
            "bonus":800
         }
      }
   }
}"""

data = json.loads(sampleJson)
print(data['company']['employee']['payble']['salary'])
```
## Expected Output
7000
