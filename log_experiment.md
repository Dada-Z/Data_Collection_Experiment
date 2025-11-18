# Data Collection Log

## Experiment Factors and Levels Table

| Factor               | Categories / Levels                                              | Notes                                                             |
|----------------------|------------------------------------------------------------------|-------------------------------------------------------------------|
| Time of Day (TOD)    | Morning peak (09:00), Afternoon (13:00), Sunset (17:00), Evening (18:00) | Times in 24-hour format.                                  |
| Road Segment         | All segments are selected in UNL City Campus.                    | Seg1 = Vine St EB, Seg2 = Vine St WB. See accompanying PNG map.   |
| Road Surface Type    | Asphalt, Concrete, Brick, or combinations                        | Mixed surfaces possible (e.g., Brick + Concrete).                 |
| Road Condition Type  | Cracks, Potholes, Brick, or combinations                         | Multiple conditions may appear together (e.g., Crack + Pothole).  |
| Traffic Level        | Low, Moderate, Congestion                                        | Most traffic conditions are low traffic volume                    |
| Vehicle Speed Target | 15–20 mph                                                        | Maintain consistent speed within campus.                          |
| Weather              | Clear, Cloudy, Rainy, After-rain (wet road), Snow                | Weather type will be included in the log.                         |
| ROS Bag Recording    | plat_form.launch + Autoware.AI recording                         | Example: `Seg1_YYYYMMDD_TIME_TYPE_WEATHER.bag`                    |


## Field Run Observation Table

| Field Run 1          | Seg1         | Seg2          |Seg3       |Seg4       |Seg5           |Seg6       |Seg7           |Seg8       |Seg9            |Seg10          |
|----------------------|--------------|---------------|-----------|-----------|---------------|-----------|---------------|-----------|----------------|---------------|
| Road Surface Type    | A            | A             | B         | A         | A             | A         | A             | A         | B              | A             |
| Road Condition Type  |crack+pothole | crack         |brick+concrete | crack | crack+pothole | crack     | crack+pothole | crack     | brick+concrete | crack+pothole |
| Date                 |2025-11-18    |2025-11-18     |2025-11-18 |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18      |2025-11-18     |
| Start Time           | 8:55 AM      | 8:56 AM       | 8:57 AM   | 8:58 AM   | 9:01 AM       | 9:01 AM   | 9:05 AM       | 9:06 AM   | 9:06 AM        | 9:07 AM       |
| Traffic Level        | L            |  L            | L         | L         | L             | L         | L             | L         | L              | L             |
| Vehicle Speed        | < 20 mph     | < 20 mph      | < 20 mph  | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph       | < 20 mph      |
| Weather              | Clear        | Clear         | Clear     | Clear     | Clear         | Clear     | Clear         | Clear     | Clear          | Clear         |
| ROS Bag File name    | seg1-2025-11-08-starting-time.bag | ... | ... |... |... |... |... |... |... |... |


| Field Run 2          | Seg1         | Seg2          |Seg3       |Seg4       |Seg5           |Seg6       |Seg7           |Seg8       |Seg9            |Seg10          |
|----------------------|--------------|---------------|-----------|-----------|---------------|-----------|---------------|-----------|----------------|---------------|
| Date                 |2025-11-18    |2025-11-18     |2025-11-18 |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18      |2025-11-18     |
| Start Time           | PM      | 8:56 AM       | 8:57 AM   | 8:58 AM   | 9:01 AM       | 9:01 AM   | 9:05 AM       | 9:06 AM   | 9:06 AM        | 9:07 AM       |
| Traffic Level        | L            |  L            | L         | L         | L             | L         | L             | L         | L              | L             |
| Vehicle Speed        | < 20 mph     | < 20 mph      | < 20 mph  | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph       | < 20 mph      |
| Weather              | Clear        | Clear         | Clear     | Clear     | Clear         | Clear     | Clear         | Clear     | Clear          | Clear         |

| Field Run 3          | Seg1         | Seg2          |Seg3       |Seg4       |Seg5           |Seg6       |Seg7           |Seg8       |Seg9            |Seg10          |
|----------------------|--------------|---------------|-----------|-----------|---------------|-----------|---------------|-----------|----------------|---------------|
| Date                 |2025-11-18    |2025-11-18     |2025-11-18 |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18      |2025-11-18     |
| Start Time           | 8:55 AM      | 8:56 AM       | 8:57 AM   | 8:58 AM   | 9:01 AM       | 9:01 AM   | 9:05 AM       | 9:06 AM   | 9:06 AM        | 9:07 AM       |
| Traffic Level        | L            |  L            | L         | L         | L             | L         | L             | L         | L              | L             |
| Vehicle Speed        | < 20 mph     | < 20 mph      | < 20 mph  | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph       | < 20 mph      |
| Weather              | Clear        | Clear         | Clear     | Clear     | Clear         | Clear     | Clear         | Clear     | Clear          | Clear         |

| Field Run 4          | Seg1         | Seg2          |Seg3       |Seg4       |Seg5           |Seg6       |Seg7           |Seg8       |Seg9            |Seg10          |
|----------------------|--------------|---------------|-----------|-----------|---------------|-----------|---------------|-----------|----------------|---------------|
| Date                 |2025-11-18    |2025-11-18     |2025-11-18 |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18     |2025-11-18 |2025-11-18      |2025-11-18     |
| Start Time           | 8:55 AM      | 8:56 AM       | 8:57 AM   | 8:58 AM   | 9:01 AM       | 9:01 AM   | 9:05 AM       | 9:06 AM   | 9:06 AM        | 9:07 AM       |
| Traffic Level        | L            |  L            | L         | L         | L             | L         | L             | L         | L              | L             |
| Vehicle Speed        | < 20 mph     | < 20 mph      | < 20 mph  | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph      | < 20 mph  | < 20 mph       | < 20 mph      |
| Weather              | Clear        | Clear         | Clear     | Clear     | Clear         | Clear     | Clear         | Clear     | Clear          | Clear         |

