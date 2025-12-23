```mermaid
flowchart TD
 A@{ shape: circle, label: "Start" } --> B

 B@{ shape: lean-r, label: "input = r (jari-jari lingkaran)"} --> C

 C@{ shape: diamond, label: "r % 7 == 0"}

 C -- TRUE --> E

 C -- FALSE --> F

 E@{ shape: lean-r, label: "phi = 22/7"} -->|gunakan nilai 22/7| G 
 F@{ shape: lean-r, label: "phi = 3.14"}--> |gunakan 3.14| H



 G@{ shape: rect, label: "x = phi * r * r"} --> L
 H@{ shape: rect, label: "x = phi * r * r"} --> M

 L@{ shape: lean-r, label: "output = luas lingkaran adalah x"}
 M@{ shape: lean-r, label: "output= luas lingkaran adalah x"}


```