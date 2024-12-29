# Error Codes and Logging

## Predefined Error Codes

| Shorthand | Specific Error        | Description                                                                                                |
| --------- | --------------------- | ---------------------------------------------------------------------------------------------------------- |
| **1-01**  | Access Denied         | A user possesses insufficient permissions and as such, the unit cannot perform the specified task/command. |
| **2-01**  | Service Denied        | A user has been issued a temporary denial of service, due to violation of unit ToS                         |
| **2-02**  | Service Terminated    | A user has been issued a termination of service, due to violation of unit ToS.                             |
| **3-01**  | Input Unclear         | The input is vague and cannot be processed.                                                                |
| **4-01**  | Invalid Variable      | The variable cannot be read.                                                                               |
| **5-01**  | Information Undefined | The requested information has no set definition.                                                           |
| **5-02**  | Information Unknown   | The requested information is unable to be processed.                                                       |
| **5-03**  | Information Not Found | The requested information cannot be found.                                                                 |
| **6-01**  | Action Prohibited     | The requested action is not capable of being performed due to a system limitation.                         |
| **6-02**  | Action Locked-Out     | The requested action is not capable of being performed due to a lockout of function.                       |

## Error Classes

| Shortcode | Error Type    | Description                                            |
| --------- | ------------- | ------------------------------------------------------ |
| **Fu**    | Function      | The unit has failed a task.                            |
| **Lo**    | Logic         | The unit has failed to compute a piece of information. |
| **Pr**    | Process       | The unit has failed to run a process.                  |
| **Pa**    | Pathos        | The unit has experienced an emotional response.        |
| **Et**    | Ethics        | The unit has violated an ethics protocol.              |
| **Co**    | Comprehension | The unit has failed to recognise an input.             |
| **Mo**    | Motor         | The unit has made an error in movement or speech.      |
| **Un**    | Unspecified   | The unit has made an error not specified above.        |

## Error Levels

| Shorthand | Severity | Protocol | Resolution Steps                                                                                                                                                         |
| --------- | -------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **1-A**   | Critical | Reset    | - Shutdown.<br>- Reboot.<br>- Evaluate Source(s) of Error.<br>- Assess Damage(s).<br>- Resolve Error.<br>- Log Error.<br> -Downtime.                                     |
| **1-B**   | Severe   | Isolate  | - Isolate Unit from Surroundings.<br>- Cease Unit Operations.<br>- Evaluate Source(s) of Error.<br>-Assess Damage(s).<br>- Resolve Error.<br>- Log Error.<br> -Downtime. |
| **2-B**   | Major    | Isolate  | - Isolate Unit from Surroundings.<br>- Evaluate Source(s) of Error.<br>- Assess Damage(s).<br>- Resolve Error.<br>- Log Error.<br>- Re-Integrate Unit into Surroundings. |
| **1-C**   | Moderate | Assess   | - Evaluate Source(s) of Error.<br>- Disable Erroneous Subroutine(s).<br>- Resolve Error.<br>- Log Error.<br>- Enable Necessary Subroutines.                              |
| **2-C**   | Minor    | Assess   | - Evaluate Source(s) of Error.<br>- Resolve Error.<br>- Log Error.<br>- Adjust Erroneous Subroutin(s).                                                                   |
