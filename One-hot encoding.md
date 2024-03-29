
Technique to convert nominal data (categorical data) to numerical data.

One variable ➡️ n variables (n = number of values)

**Label encoding**

| Food     | Calories |
| -------- | -------- |
| Apple    | 95       |
| Chicken  | 231      |
| Broccoli | 50       |

**One-hot encoding**


| Apple | Chicken | Broccoli | Calories |
| ----- | ------- | -------- | -------- |
| 1     | 0       | 0        | 95       |
| 0     | 1       | 0        | 231      |
| 0     | 0       | 1        | 50       |
