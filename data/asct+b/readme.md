# Organ data

__Source__<br>
The data tables of the organs have been downloaded from the website of the [ASCT+B Reporter](https://hubmapconsortium.github.io/ccf-asct-reporter/), but they can also be accessed from the website of the  [Hubmap Consortium](https://hubmapconsortium.github.io/ccf/pages/ccf-anatomical-structures.html) using the [API](https://asctb-api.herokuapp.com/#/operations/csv-get).

This folder contains the node and edge lists of the organs in a JSON format:

```json
{
 "data": {
   "nodes": [
     {
       "id": 0,
       "type": "AS",
       "name": "Body",
       "metadata": {	
         "name": "Body",
         "ontologyId": "UBERON:0013702",
         "ontologyType": "UBERON",
         "ontologyTypeId": "0013702",
         "label": "body proper",
         "references": []
       }
     },
     {
       "id": 1,
       "type": "AS",
       "name": "brain",
	. . .
	}
	. . .
   ],
   "edges": [
     {
       "source": 0,
       "target": 1
     },
     {
       "source": 1,
       "target": 2
     },
     {
       "source": 2,
       "target": 3
	},
	. . .
 
   ]
 }
}

 
```




