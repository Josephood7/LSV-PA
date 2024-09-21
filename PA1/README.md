# Programming Assignment 1

## 5-to-3 compressor design methodology

![Diagram](https://github.com/user-attachments/assets/f7dec825-542c-4794-b7ca-62f10cfcaebc)

## ABC Boolean Function Representations
### Logic Network

![aig](https://github.com/user-attachments/assets/24704445-a1ff-4517-a728-493497a93b18)

---

### And-Inverter Graphs (AIG)
`aig`  
> Composed of:
> * 2-input ANDs (nodes)
> * inverters (edges)
>> ![90574F94-2318-452B-BA4E-653C8BB45821](https://github.com/user-attachments/assets/a5957173-a29e-451c-a58c-6acfc6fafae0)

![aig](https://github.com/user-attachments/assets/b3b347f3-c6f7-45cc-962d-cd80fba87c6f)


### Global AIG
`strash`
> No node boundary. A more scattered map.
>> ![strash](https://github.com/user-attachments/assets/523337c9-cddd-4d33-8c7d-59195df55df0)

---

### Binary Decision Diagraph (BDD)
`bdd`
> Shannon expression
> * Canonical
>> ![060D04D7-4325-4122-835C-9E58E8400A8D](https://github.com/user-attachments/assets/6535deda-844b-4acc-a231-0a8ff139f58f)

![bdd](https://github.com/user-attachments/assets/481a6440-342c-493d-951d-76de46d0f892)

### Global BDD
`collapse`
> Simplified with cut and boundaries.
>> ![collapse](https://github.com/user-attachments/assets/3bed235d-fd38-4fb6-bf74-fe0d1e9238bf)

---

### SOP  
![sop](https://github.com/user-attachments/assets/9efbb006-ba59-4f61-affd-5f960ee906b6)
