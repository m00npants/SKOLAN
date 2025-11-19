## 4. Positive, Negative, or Zero Check
### ✔ Pseudocode

```text

START
    INPUT number
    IF number > 0 THEN
        PRINT "Positive"
    ELSE IF number < 0 THEN
        PRINT "Negative"
    ELSE
        PRINT "Zero"
    ENDIF
END

```
### ✔ Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C{number > 0?}
    C -->|Yes| D[/Print "Positive"/]
    C -->|No| E{number < 0?}
    E -->|Yes| F[/Print "Negative"/]
    E -->|No| G[/Print "Zero"/]
    D --> H([End])
    F --> H
    G --> H
