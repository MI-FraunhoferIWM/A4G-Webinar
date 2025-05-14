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

# 2. Object Properties

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


# 3. Datatype Properties

| **Property**      | **Description**                                              |
| ----------------- | ------------------------------------------------------------ |
| `batteryCapacity` | Capacity of a battery (e.g., in Wh or Ah).                   |
| `motorPower`      | Power rating of the motor (e.g., in watts).                  |
| `weight`          | Weight of the e-bike.                                        |
| `rangePerCharge`  | Distance that can be traveled on a single battery charge.    |
| `averageSpeed`    | Average speed during a test or ride.                         |
| `riderWeight`     | Weight of the user.                                          |
| `testDuration`    | Duration of the performance test.                            |
| `frameMaterial`   | Material of the e-bike frame (e.g., aluminum, carbon fiber). |
| `sensorType`      | Type or function of a sensor (e.g., torque, speed).          |
