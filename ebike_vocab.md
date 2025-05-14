 # 1. Class Definitions
| **Class**            | **Description**                                             |
| -------------------- | ----------------------------------------------------------- |
| `EBike`              | An electric bicycle.                                        |
| `Battery`            | The battery used in the e-bike.                             |
| `Motor`              | The motor used to provide electric assistance.              |
| `Frame`              | The main structural component of the e-bike.                |
| `Sensor`             | Device used to monitor bike performance or environment.     |
| `RidePerformance`    | Data from a ride used for evaluating performance.           |
| `Component`          | A general physical part of the e-bike.                      |
| `Manufacturer`       | Entity or company building the e-bike or its parts.         |
| `TestScenario`       | Setup or conditions under which a test is run.              |
| `UserProfile`        | Information about the rider (e.g., weight, experience).     |
| `BuildSpecification` | Specifications used in configuring or assembling an e-bike. |

# 2. Data

| **Property**   | **Description**                                                       |
| -------------- | --------------------------------------------------------------------- |
| `hasBattery`   | Links an e-bike to a specific battery.                                |
| `hasMotor`     | Links an e-bike to a specific motor.                                  |
| `hasFrame`     | Associates an e-bike with its frame.                                  |
| `hasSensor`    | Connects an e-bike to one or more sensors.                            |
| `hasComponent` | Generic link to any part or module used in the e-bike.                |
| `builtBy`      | Associates a product or component with a manufacturer.                |
| `evaluatedBy`  | Connects ride performance data with the scenario it was tested under. |
| `riddenBy`     | Links the e-bike or test data to a user profile.                      |
