# Primary Memory

## Introduction

Primary Memory, also known as Main Memory, is the memory directly accessed by the CPU. It stores data, instructions, and programs that are currently being used by the computer.

Primary memory is faster than secondary storage and plays a crucial role in computer performance.

---

# What is Primary Memory?

## Definition

Primary Memory is the internal memory of a computer that stores data and instructions currently needed by the CPU.

## Characteristics

* Directly accessible by CPU
* Fast access speed
* Limited storage capacity
* More expensive than secondary storage
* Essential for computer operation

---

# Types of Primary Memory

Primary Memory is mainly divided into:

```text id="m4kqzp"
Primary Memory
│
├── RAM
│   ├── SRAM
│   └── DRAM
│
└── ROM
    ├── PROM
    ├── EPROM
    └── EEPROM
```

---

# 1. RAM (Random Access Memory)

## Definition

RAM is a temporary memory used to store data and programs currently being used by the computer.

## Characteristics

* Read and write memory
* Temporary storage
* Fast access
* Volatile memory

### Volatile Memory

Volatile memory loses its contents when power is turned off.

## Examples

* Running applications
* Open documents
* Active browser tabs

## Advantages

* High speed
* Improves system performance

## Disadvantages

* Data is lost after power shutdown

---

# 2. SRAM (Static RAM)

## Definition

SRAM is a type of RAM that stores data using flip-flops.

## Features

* Very fast
* Expensive
* Low storage capacity
* Does not require frequent refreshing

## Applications

* CPU Cache Memory

## Advantages

* High speed
* Reliable performance

## Disadvantages

* Expensive

---

# 3. DRAM (Dynamic RAM)

## Definition

DRAM is a type of RAM that stores data using capacitors.

## Features

* Slower than SRAM
* Less expensive
* Higher storage capacity
* Requires periodic refreshing

## Applications

* Main system memory

## Advantages

* Cost-effective
* Large capacity

## Disadvantages

* Slower than SRAM

---

# Difference Between SRAM and DRAM

| SRAM              | DRAM                |
| ----------------- | ------------------- |
| Faster            | Slower              |
| Expensive         | Cheaper             |
| Uses Flip-Flops   | Uses Capacitors     |
| No Refresh Needed | Refresh Needed      |
| Used in Cache     | Used as Main Memory |

---

# 4. ROM (Read Only Memory)

## Definition

ROM is a permanent memory that stores important instructions required to start the computer.

## Characteristics

* Non-volatile memory
* Data remains even after power is off
* Mainly used for firmware

### Non-Volatile Memory

Non-volatile memory retains data even when power is removed.

## Applications

* BIOS
* Firmware
* Boot programs

## Advantages

* Permanent storage
* Reliable

## Disadvantages

* Difficult to modify

---

# 5. PROM (Programmable Read Only Memory)

## Definition

PROM is a type of ROM that can be programmed only once.

## Features

* Blank when manufactured
* User can write data once
* Cannot be modified afterward

## Applications

* Embedded systems
* Hardware devices

## Advantages

* Customizable once

## Disadvantages

* Cannot be reprogrammed

---

# 6. EPROM (Erasable Programmable Read Only Memory)

## Definition

EPROM is a ROM that can be erased using ultraviolet (UV) light and programmed again.

## Features

* Reusable
* Requires UV light for erasing

## Applications

* Older electronic devices

## Advantages

* Reprogrammable

## Disadvantages

* Erasing process is slow

---

# 7. EEPROM (Electrically Erasable Programmable Read Only Memory)

## Definition

EEPROM is a ROM that can be erased and reprogrammed electrically.

## Features

* Electrically erasable
* Reusable many times
* Faster than EPROM

## Applications

* Modern firmware
* BIOS chips
* Embedded systems

## Advantages

* Easy modification
* Reprogrammable

## Disadvantages

* Limited write cycles

---

# RAM vs ROM

| RAM                      | ROM                           |
| ------------------------ | ----------------------------- |
| Volatile                 | Non-Volatile                  |
| Temporary Storage        | Permanent Storage             |
| Read and Write           | Mostly Read Only              |
| Faster                   | Slower                        |
| Data Lost When Power Off | Data Retained After Power Off |

---

# Working of Primary Memory

### Step 1

Program is loaded into RAM.

### Step 2

CPU reads instructions from RAM.

### Step 3

CPU processes the instructions.

### Step 4

Results are temporarily stored in RAM.

### Step 5

Important data may be saved to secondary storage.

---

# Importance of Primary Memory

Primary Memory:

* Stores active programs
* Supports fast processing
* Helps CPU access data quickly
* Improves system performance

Without primary memory, a computer cannot execute programs efficiently.

---

# Summary

* Primary Memory is directly accessed by the CPU.
* RAM is temporary and volatile.
* SRAM is fast and used in cache memory.
* DRAM is slower and used as main memory.
* ROM is permanent and non-volatile.
* PROM can be programmed once.
* EPROM can be erased using UV light.
* EEPROM can be erased electrically and reprogrammed.

---

# Interview Questions

### Q1. What is Primary Memory?

Primary Memory is the memory directly accessed by the CPU to store active data and instructions.

### Q2. What is RAM?

RAM is a volatile memory used for temporary storage of data and programs.

### Q3. Why is RAM called volatile memory?

Because it loses data when power is turned off.

### Q4. What is ROM?

ROM is a non-volatile memory used to store permanent instructions.

### Q5. What is the difference between RAM and ROM?

RAM is temporary and volatile, while ROM is permanent and non-volatile.

### Q6. Which is faster, SRAM or DRAM?

SRAM.

### Q7. Where is SRAM commonly used?

CPU Cache Memory.

### Q8. What is PROM?

A ROM that can be programmed only once.

### Q9. How is EPROM erased?

Using ultraviolet (UV) light.

### Q10. How is EEPROM erased?

Electrically.

---

# Quick Revision

```text id="3jz0q4"
PRIMARY MEMORY

RAM  → Temporary → Volatile
ROM  → Permanent → Non-Volatile

RAM
├── SRAM → Fast → Cache Memory
└── DRAM → Main Memory

ROM
├── PROM  → Program Once
├── EPROM → UV Erase
└── EEPROM → Electrical Erase
```

### Memory Trick

```text id="76jvfz"
SRAM = Speed
DRAM = Daily RAM

PROM  = Program Once
EPROM = Erase with UV Light
EEPROM = Erase Electrically
```
