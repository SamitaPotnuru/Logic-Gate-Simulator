# ⚡ Logic Gate Simulator

A fully interactive **Logic Gate Simulator** built with **HTML, CSS, and JavaScript**. Design, simulate, and visualize digital circuits with logic gates, including AND, OR, NOT, NAND, NOR, and XOR gates. Generate truth tables automatically for your circuits.  

---

## 🔹 Features

- **Add Nodes**:  
  - Input switches (user-controlled binary 0/1)  
  - Output nodes (display results)  
  - Logic gates: AND, OR, NOT, NAND, NOR, XOR  

- **Interactive Wiring**:  
  - Connect gate outputs to inputs by dragging wires  
  - Remove connections by clicking on pins  
  - Signal flow visualization with animated pulses  

- **Gate Operations**:  
  - Supports multiple inputs per gate (adjustable for AND, OR, NAND, NOR, XOR)  
  - Correctly evaluates gate logic in real time  

- **Circuit Simulation**:  
  - Auto-calculates outputs whenever an input is toggled  
  - Handles multi-step circuits with feedback loops  

- **Truth Table Generation**:  
  - Click the **⚙ Truth Table** button to generate a complete truth table  
  - Works for any combination of input and output nodes  

- **UI Features**:  
  - Drag gates to rearrange your circuit  
  - Pan the canvas by clicking and dragging empty space  
  - Context menu to add/remove inputs or delete gates  
  - Sidebar with gate theory and mini truth tables  

---

## 🔹 How to Use

1. Open `index.html` in a modern browser.  
2. Use the toolbar to add **Input**, **Output**, or **Logic Gates** to the canvas.  
3. Connect gates by clicking and dragging from an **output pin** to an **input pin**.  
4. Toggle input nodes by clicking them to simulate 0 ↔ 1.  
5. Click **⚙ Truth Table** in the toolbar to generate the truth table of your circuit.  
6. Drag gates to reposition or right-click to adjust inputs or delete a gate.  

---

## 🔹 Supported Gates & Logic

| Gate  | Logic Description                  | Truth Table Example |
|-------|-----------------------------------|------------------|
| AND   | 1 if **all inputs are 1**          | A·B               |
| OR    | 1 if **any input is 1**            | A+B               |
| NOT   | Flips input                        | ¬A                |
| NAND  | AND then invert                     | ¬(A·B)           |
| NOR   | OR then invert                      | ¬(A+B)           |
| XOR   | 1 if inputs differ                  | A⊕B               |

---

## 🔹 Controls & Shortcuts

- **Click Input Node** – toggle 0 ↔ 1  
- **Drag Gate** – move gates around the canvas  
- **Right Click Gate** – open context menu to add/remove inputs or delete  
- **Delete / Backspace** – delete selected gate  
- **Pan Canvas** – click and drag empty space  

---

## 🔹 Folder Structure

```text
logic-gate-simulator/
│
├─ index.html       # Main HTML file
└─ README.md        # Project documentation
