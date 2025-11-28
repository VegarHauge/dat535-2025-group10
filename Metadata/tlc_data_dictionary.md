# TLC Yellow Taxi Data Dictionary

| Field Name                  | Description                                                                                                                                                                |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **VendorID**                | A code indicating the TPEP provider that provided the record. 1 = Creative Mobile Technologies, LLC. 2 = Curb Mobility, LLC.  6 = Myle Technologies Inc.  7 = Helix             |
| **tpep\_pickup\_datetime**  | The date and time when the meter was engaged.                                                                                                                              |
| **tpep\_dropoff\_datetime** | The date and time when the meter was disengaged.                                                                                                                           |
| **passenger\_count**        | The number of passengers in the vehicle.                                                                                                                                   |
| **trip\_distance**          | The elapsed trip distance in miles reported by the taximeter.                                                                                                              |
| **RatecodeID**              | The final rate code in effect at the end of the trip. 1 = Standard rate. 2 = JFK. 3 = Newark. 4 = Nassau or Westchester. 5 = Negotiated fare. 6 = Group ride. 99 = Null/unknown         |
| **store\_and\_fwd\_flag**   | Indicates whether the trip record was held in vehicle memory before sending to the vendor ("store and forward").Y = store and forward tripN = not a store and forward trip |
| **PULocationID**            | TLC Taxi Zone in which the taximeter was engaged.                                                                                                                          |
| **DOLocationID**            | TLC Taxi Zone in which the taximeter was disengaged.                                                                                                                       |
| **payment\_type**           | A numeric code signifying how the passenger paid for the trip. 0 = Flex Fare trip. 1 = Credit card. 2 = Cash. 3 = No charge. 4 = Dispute. 5 = Unknown. 6 = Voided trip                  |
| **fare\_amount**            | The time-and-distance fare calculated by the meter.                                                                                                                        |
| **extra**                   | Miscellaneous extras and surcharges.                                                                                                                                       |
| **mta\_tax**                | Tax automatically triggered based on the metered rate in use.                                                                                                              |
| **tip\_amount**             | Tip amount. Automatically populated for credit card tips; cash tips not included.                                                                                          |
| **tolls\_amount**           | Total amount of all tolls paid in trip.                                                                                                                                    |
| **improvement\_surcharge**  | Improvement surcharge assessed at the flag drop. Began in 2015.                                                                                                            |
| **total\_amount**           | The total amount charged to passengers. Does not include cash tips.                                                                                                        |
| **congestion\_surcharge**   | Total amount collected in trip for NYS congestion surcharge.                                                                                                               |
| **airport\_fee**            | For pickups only at LaGuardia and John F. Kennedy airports.                                                                                                                |
| **cbd\_congestion\_fee**    | Per-trip charge for MTA's Congestion Relief Zone (starting Jan. 5, 2025).                                                                                                  |

