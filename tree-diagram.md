graph TD

START --> Q1
Q1 -->|Productive/Mixed| Q2A
Q1 -->|Tough/Frustrating| Q2B

Q2A --> R1
Q2B --> R2

R1 --> Q3
R2 --> Q3

Q3 --> Q4
Q4 -->|Contribution| Q5
Q4 -->|Expectation| Q6

Q5 --> R3
Q6 --> R4

R3 --> Q7
R4 --> Q7

Q7 --> Q8
Q8 -->|Self| Q9
Q8 -->|Others| Q10

Q9 --> R5
Q10 --> R6

R6 --> SUMMARY
SUMMARY --> END