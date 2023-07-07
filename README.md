# MYSQL XID EXTRACT

Go to the mysql terminal and send this command to get the XA TRANSACTION STUCKED:
`xa recover convert xid;`

A result like this will be appear:

```
+----------+--------------+--------------+------------------------------------------------------------------------------------------+
| formatID | gtrid_length | bqual_length | data                                                                                     |
+----------+--------------+--------------+------------------------------------------------------------------------------------------+
|        1 |           40 |            3 | 0x65386234623938362D343062382D346335612D383437342D3730363163346264356563363A313236313237 |
+----------+--------------+--------------+------------------------------------------------------------------------------------------+
```

get the content inside the column **data**
