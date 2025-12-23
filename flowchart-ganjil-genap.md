


```mermaid
flowchart TD
    A@{ shape: circle, label: "Start" } -->C

    C@{ shape: lean-r, label: "Angka" } --> D

    D@{ shape: rect, label: "Masukkan input Angka Random" } --> E

    E@{ shape: diamond, label: "Apakah angka tersebut dapat dibagi 2 tanpa sisa?" } 

    E -- YA --> G

    E -- TIDAK --> F

    G@{ shape: rect, label: "angka genap" } --> H

    F@{ shape: rect, label: "angka ganjil" } --> I

    H@{ shape: lean-r, label: "bilangan genap"} --> B

    I@{ shape: lean-r, label: "bilangan ganjil"} --> B



    B@{ shape: circle, label: "Stop" }

```