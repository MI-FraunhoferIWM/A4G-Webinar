

### 1. Classes

##### Explaination:

Think of classes as categories or types of things in the e-bike world. Each class represents a group of related objects or ideas. In simple terms, classes answer the question, "What kinds of things are we talking about?"

##### Terms:

| **#** | **Class**               | **Description**                                                    |
| ----- | ----------------------- | ------------------------------------------------------------------ |
| 1     | `EBike`                 | An electric bicycle.                                               |
| 2     | `Battery`               | The battery used in the e-bike.                                    |
| 3     | `Motor`                 | The motor used to provide electric assistance.                     |
| 4     | `Frame`                 | The main structural component of the e-bike.                       |
| 5     | `Sensor`                | Device used to monitor bike performance or environment.            |
| 6     | `RidePerformance`       | Data from a ride used for evaluating performance.                  |
| 7     | `Component`             | A general physical part of the e-bike.                             |
| 8     | `Manufacturer`          | Entity or company building the e-bike or its parts.                |
| 9     | `TestScenario`          | Setup or conditions under which a test is run.                     |
| 10    | `UserProfile`           | Information about the rider (e.g., weight, experience).            |
| 11    | `BuildSpecification`    | Specifications used in configuring or assembling an e-bike.        |
| 12    | `CarbonFiber`           | Lightweight material used for frames and handlebars.               |
| 13    | `AluminumAlloy`         | Metal commonly used for frames, known for its light weight.        |
| 14    | `Titanium`              | Durable, lightweight material used for premium parts.              |
| 15    | `CompositeMaterial`     | Engineered material like carbon fiber and polymers.                |
| 16    | `AntiLockBraking`       | System to prevent wheel lock during braking.                       |
| 17    | `LEDLighting`           | Energy-efficient lighting for roads and signals.                   |
| 18    | `SmartSensor`           | Technology for detecting proximity, speed, or hazards.             |
| 19    | `StabilityControl`      | Mechanisms to maintain balance and prevent tipping.                |
| 20    | `WearResistantCoating`  | Coating applied to reduce wear and tear on components.             |
| 21    | `Weatherproofing`       | Features that protect the e-bike against environmental conditions. |
| 22    | `ModularComponent`      | Parts designed for easy replacement or upgrades.                   |
| 23    | `ReflectiveElement`     | Materials added to enhance visibility in low light.                |
| 24    | `ErgonomicDesign`       | Features that improve comfort and control.                         |
| 25    | `PunctureResistantTire` | Tires designed to prevent flats from sharp objects.                |

---

### 2. Object Properties
##### Explaination:
Object properties describe how different things (classes) are connected or related. They show relationships between one class and another. Think of object properties as the "verbs" that link "nouns" (classes) together, like "an e-bike has a motor."

Examples:
- hasBattery links an e-bike (EBike class) to a specific battery (Battery class).
- builtBy connects an e-bike (EBike class) to its manufacturer (Manufacturer class).

##### Terms:

| **#** | **Property**   | **Description**                                                        |
| ----- | -------------- | ---------------------------------------------------------------------- |
| 1     | `hasBattery`   | Links an e-bike to a specific battery.                                 |
| 2     | `hasMotor`     | Links an e-bike to a specific motor.                                   |
| 3     | `hasFrame`     | Associates an e-bike with its frame.                                   |
| 4     | `hasSensor`    | Connects an e-bike to one or more sensors.                             |
| 5     | `hasComponent` | Generic link to any part or module used in the e-bike.                 |
| 6     | `builtBy`      | Associates a product or component with a manufacturer.                 |
| 7     | `evaluatedBy`  | Connects ride performance data with the scenario it was tested under.  |
| 8     | `riddenBy`     | Links the e-bike or test data to a user profile.                       |
| 9     | `hasLighting`  | Links the e-bike to its lighting system.                               |
| 10    | `usesMaterial` | Indicates the material used in construction (e.g., frame, components). |
| 11    | `includes`     | Includes modular or additional components (e.g., motor, sensors).      |
| 12    | `poweredBy`    | Links the e-bike to its energy source (e.g., battery).                 |

---

### 3. Datatype Properties
##### Explaination:
Data properties describe specific details or attributes of a thing. They are facts or measurements about an object. Data properties answer questions like "How much?" or "What kind?"

Examples:
- batteryCapacity gives the amount of energy a battery can hold (e.g., in Wh).
- weight tells how heavy an e-bike is (e.g., in kilograms).

##### Terms:

| **#** | **Property**          | **Description**                                                |
| ----- | --------------------- | -------------------------------------------------------------- |
| 1     | `batteryCapacity`     | Capacity of a battery (e.g., in Wh or Ah).                     |
| 2     | `motorPower`          | Power rating of the motor (e.g., in watts).                    |
| 3     | `weight`              | Weight of the e-bike.                                          |
| 4     | `rangePerCharge`      | Distance that can be traveled on a single battery charge.      |
| 5     | `averageSpeed`        | Average speed during a test or ride.                           |
| 6     | `riderWeight`         | Weight of the user.                                            |
| 7     | `testDuration`        | Duration of the performance test.                              |
| 8     | `frameMaterial`       | Material of the e-bike frame (e.g., aluminum, carbon fiber).   |
| 9     | `sensorType`          | Type or function of a sensor (e.g., torque, speed).            |
| 10    | `dragCoefficient`     | Air resistance (aerodynamics) affecting performance.           |
| 11    | `reflectivity`        | Measure of visibility enhancement (e.g., % reflectance).       |
| 12    | `stabilityRange`      | Angular range to maintain balance during operation.            |
| 13    | `impactResistance`    | Ability of components to withstand collisions (measured in N). |
| 14    | `corrosionResistance` | Resistance to rust and environmental degradation.              |

