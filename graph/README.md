# Graph Model

```
CREATE 
  (`0` :Activity {title:"Introducing the Hard Way"}) ,
  (`1` :Activity {title:"Setting Up"}) ,
  (`2` :Activity {title:"Hello, World!"}) ,
  (`3` :Activity {title:"Comments and Pound Characters"}) ,
  (`0`)-[:`RELATED_TO` ]->(`1`),
  (`1`)-[:`RELATED_TO` ]->(`2`),
  (`2`)-[:`RELATED_TO` ]->(`3`)
```