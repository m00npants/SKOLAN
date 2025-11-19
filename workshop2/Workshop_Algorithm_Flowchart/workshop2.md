## 2. Calculate Total and Average Marks

```text
Start
Input mark1, mark2, mark3
total < mark1 + mark2 + mark3average < total / 3
Print < total, average
End
```


```mermaid
flowchart TD
    A([Start]) --> B[/Input mark1, mark2, mark3/]
    B --> C[Calculate total = mark1 + mark2 + mark3]
    C --> D[Calculate average = total / 3]
    D --> E[/Print total, average/]
    E --> F([End])
    ```

---

## 3. Display Multiplication Table
```text
Start
Input number
For i From 1 To 10 Do
Print number x i
EndFor
End
```

```mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C[Set i = 1]
    C --> D{Is i ≤ 10?}
    D -->|Yes| E[Print number × i]
    E --> F[i = i + 1]
    F --> D
    D -->|No| G([End])

    ```