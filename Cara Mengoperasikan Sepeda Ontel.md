##Pseudocode

Start

Siapkan sepeda

Periksa kondisi sepeda(rusak==false)

Naik ke sepeda

Letakkan kaki pada pedal

Dorong pedal dengan kaki kanan

Mulai mengayuh sepeda secara bergantiaan kaki kanan dan kiri

if(tujuan==sampai) then rem

Turun dari sepeda

End

##flowchart

```mermaid
flowchart TD
    A[Start] --> B[Siapkan sepeda]
    B --> C{Sepeda rusak?}
    C -- Ya --> D[Perbaiki sepeda]
    D --> E[Naik ke sepeda]
    C -- Tidak --> E[Naik ke sepeda]
    E --> F[Letakkan kaki pada pedal]
    F --> G[Dorong pedal dengan kaki kanan]
    G --> H[Kayuh bergantian kaki kanan dan kiri]
    H --> I{Tujuan sampai?}
    I -- Ya --> J[Gunakan rem]
    I -- Tidak --> H
    J --> K[Turun dari sepeda]
    K --> L[End]
