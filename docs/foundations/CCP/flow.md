# 1. Training Flow

<p style="font-weight:bold;">Clearance Delivery</p>

``` mermaid
graph LR
  A("`VATUSA Basic ATC/S1 
  Course and Exam`") --> B{DEL-1};
  B --> C{DEL-2};
  C --> D[[DEL-3]];
```

<p style="font-weight:bold;">Simple Ground</p>

``` mermaid
graph LR
  A("`HCF DEL
  Certification`") --> B{S GND-1};
  B --> C>S GND-2];
  C --> D(S GND-2R);
```

<p style="font-weight:bold;">Advanced Ground</p>

``` mermaid
graph LR
  A{GND-1} --> B{GND-2};
  B --> C>GND-3];
```

<p style="font-weight:bold;">Simple Local</p>

``` mermaid
graph LR
  A("`VATUSA Local Control 
  Course and S2 Exam`") --> B{S TWR-1};
  B --> C{S TWR-2};
  C --> D>S TWR-3];
```

<p style="font-weight:bold;">Advanced Local</p>

``` mermaid
graph LR
  A{TWR-1} --> B{TWR-2};
  B --> C((TWR-3));
  C --> D[["`TWR Rating 
  Examination`"]];
```

<p style="font-weight:bold;">Approach</p>

``` mermaid
graph LR
  A("`VATUSA Approach Control 
  Course and S3 Exam`") --> B{APP-1};
  B --> C{APP-2};
  C --> D{APP-3};
  E{APP-4} --> F{APP-5};
  F --> G{APP-6};
  G --> H{APP-7};
  I((APP-8)) --> J{APP-9};
  J --> K[["`APP Rating 
  Examination`"]];
```

<p style="font-weight:bold;">Enroute</p>

``` mermaid
graph LR
  A("`VATUSA Center Control 
  Course and C1 Exam`") --> B{HCF-1};
  B --> C{HCF-2};
  C --> D{HCF-3};
  E{HCF-4} --> F{HCF-5};
  F --> G{HCF-6};
  G --> H((HCF-7));
  I[["`HCF Rating 
  Examination`"]];
```

<p style="font-weight:bold;">Legend</p>

``` mermaid
graph LR
  A(Requirement) --> B{Lesson};
  B --> C(("`Mock Rating
  Examination`"));
  C --> D>"`Certification 
  Change or Solo
  Certification`"];
  I[["`VATSIM/VATUSA
  Rating Change`"]];
```