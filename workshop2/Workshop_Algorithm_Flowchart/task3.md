```text

START
    INPUT number
    FOR i FROM 1 TO 10 DO
        PRINT number × i
    ENDFOR
END

```

```mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C[i ← 1]
    C --> D{Is i ≤ 10?}
    D -->|Yes| E[/Print number × i/]
    E --> F[i ← i + 1]
    F --> D
    D -->|No| G([End])

