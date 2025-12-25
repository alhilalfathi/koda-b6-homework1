# Homework 1
## Flowchart while

```mermaid
flowchart TD
    mulai@{ shape: circle}
    input@{ shape: lean-r, label: "Input: i = 1"}
    if@{ shape: diamond, label: "i <= 4"}
    true@{ shape: lean-r, label: "Output: #quot;Hai#quot;"}
    iterasi@{ label: "i++"}
    selesai@{ shape: dbl-circ}

mulai-->input-->if
if--false--->selesai
if--true-->true-->iterasi-->if
```