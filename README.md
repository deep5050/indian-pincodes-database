# indian-pincodes-database
#  SAMPLE JSON FORMAT 

```
 {
            "PostOfficeName": "Canal Colony",
            "Pincode": "226001",
            "City": "Lucknow",
            "District": "Lucknow",
            "State": "Uttar Pradesh"
        }
```
        
#   SAMPLE SQL FORMAT
```
/* CREATE TABLE */
CREATE TABLE table_name(
PostOfficeName VARCHAR(100),
Pincode DOUBLE,
City VARCHAR(100),
District VARCHAR(100),
State VARCHAR(100)
);

INSERT INTO table_name(PostOfficeName, Pincode, City, District, State)
VALUES
(
'Connaught Place', 110001, 'New Delhi', 'New Delhi', 'Delhi'
);


INSERT INTO table_name(PostOfficeName, Pincode, City, District, State)
VALUES
(
'Constitution House', 110001, 'New Delhi', 'Central Delhi', 'Delhi'
);
````
