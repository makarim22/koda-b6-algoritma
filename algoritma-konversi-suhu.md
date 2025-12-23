## Minitask 

## buat algoritma deskriptif yang mengonversi suhu dari celcius ke kelvin, reamur, dan fahrenheit

1. Mulai
2. Masukkan suhu celcius
3. tampilkan, "suhu dalam reamur adalah"
4. kalikan suhu celcius dengan 4/5
5. tampilkan, "suhu dalam Kelvin adalah"
6. tambahkan suhu celcius dengan 273,15
7. tampilkan, "suhu dalam Fahrenheit adalah"
8. kalikan suhu celcius dengan 9/5 dan tambahkan dengan 32
9. selesai


```mermaid
flowchart TD

    A@{ shape: circle, label: "Start" } --> 
    B@{ shape: lean-r, label: "Input: Celcius" } --> F
    C@{ shape: rect, label: "Reamur = Celcius * 4/5" }
    D@{ shape: rect, label: "Kelvin = Celcius + 273.15" }
    E@{ shape: rect, label: "Fahrenheit = (Celcius * 9/5) + 32" }    
   
    F@{ shape: diamond, label: "Pilih satu: Reamur, Kelvin, atau Fahrenheit?" } 

    X@{ shape: lean-r, label: "Output: \"Suhu dalam Reamur adalah\" , Reamur" }
    Y@{ shape: lean-r, label: "Output: \"Suhu dalam Kelvin adalah\" , Kelvin" }
    Z@{ shape: lean-r, label: "Output: \"Suhu dalam Fahrenheit adalah\" , Fahrenheit" }
   
    F -- "Reamur" --> C --> X --> J
    F -- "Kelvin" --> D --> Y --> J
    F -- "Fahrenheit" --> E --> Z --> J

    J@{ shape: circle, label: "Stop" } 

 

```
