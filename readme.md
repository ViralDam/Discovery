# Expo SDK updated to v49
---

## Setup
In case you get error of `maps-api-for-javascript` package not found on doing `npm install`. Run the following command and then run `npm install` 

``` bash
npm config set @here:registry https://repo.platform.here.com/artifactory/api/npm/maps-api-for-javascript/
```

---
## Run
After app runs it seems like we have hardcoded and limited the routes that we can search to the following (Maybe cause thats the only data we have):
- Sunnyvale Transit Center
- Valley Fair
- Santa Clara Transit Center
- Palo Alto Transit Center
- Milpitas BART
- Palo Alto Transit Center

***Note: Dont add any space after typing. It wont work.***

---