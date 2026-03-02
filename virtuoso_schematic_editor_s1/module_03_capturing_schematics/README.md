# Module 03 – Capturing Schematics

## Lab 3-1 – Two-Input NAND Gate

### Objective
To design a two-input CMOS NAND gate using Virtuoso Schematic Editor.

---

## Design Approach

- PMOS transistors connected in parallel (pull-up network)
- NMOS transistors connected in series (pull-down network)
- Output node connected between pull-up and pull-down networks

This structure ensures NAND logic functionality.

---

## CMOS NAND Logic Behavior

| A | B | Output |
|---|---|--------|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

---

## Learning Outcome

- Understood CMOS logic implementation at transistor level
- Practiced device placement and wiring in Virtuoso
- Learned schematic verification and design rule checking
