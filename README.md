#  6 sigma study notes
## 第一章 六西格玛管理概论
### 1.1 六西格玛管理的发展

```graphic
dfdsg 


````
flowchart TD
    A[原材料<br>Raw Material] --> B[织网<br>Weaving mesh]
    B --> C[清洗<br>Cleaning]
    C --> D[上胶<br>Gummed]
    D --> E[碾压<br>Rolling]
    E --> F1[第1次切割<br>Cutting CNC2]
    F1 --> F2[第2次切割<br>Cutting CNC2]
    F2 --> F3[第3次切割<br>Cutting CNC2]
    F3 --> F4[第4次切割<br>Cutting CNC2]
    F4 --> F5[第5次切割<br>Cutting CNC2]
    F5 --> G[成品]

    style A fill:#e1f5fe
    style G fill:#c8e6c9
