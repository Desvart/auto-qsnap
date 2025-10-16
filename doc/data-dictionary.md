| Entity            | Attribute     | Data Type            | Description                                                      |  
|-------------------|---------------|----------------------|------------------------------------------------------------------|
|                   |               |                      |                                                                  |
| Data              | data_id       | INT                  | (PK) Unique identifier for each data                             |
|                   | creation_date | DATE                 | Date when object has been created                                |
|                   | type          | VARCHAR(255)         | Type of the data (enum)                                          |
|                   | value         | ?                    |                                                                  |
|                   | Sources       | {Data, VARCHAR(255)} |                                                                  |
|                   |               |                      |                                                                  |
| Metric            | metric_id     | INT                  |                                                                  |
|                   | description   | TEXT                 |                                                                  |
|                   | formula       | TEXT                 |                                                                  |
|                   | approximate   | TEXT                 | Description of the underlying intention for such metric to exist |
|                   |               |                      |                                                                  |
| User_satisfaction |               |                      |                                                                  |
|                   |               |                      |                                                                  |
| Snapshot          |               |                      |                                                                  |
