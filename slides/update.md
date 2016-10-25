#  Update

```
db.put(doc, [docId], [docRev], [options], [callback]);

db.get('eoe', function(err, doc) {
  if (err) { return console.log(err); }
  db.put({
    _id: 'wow',
    _rev: doc._rev,
    talk: "No Service: Supporting Offline App Usage"
  }, function(err, response) {
    if (err) { return console.log(err); }
    // handle response
  });
});
```
