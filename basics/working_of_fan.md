# How a Ceiling Fan Works: The Complete Physics Guide

This document breaks down the exact step-by-step mechanism of an AC ceiling fan motor, converting alternating current (AC) into continuous, one-way rotational motion.

---

## 🏗️ 1. Core Internal Components

*   **The Stator (Stationary Coils):** An inner ring of fixed copper wire coils arranged in a circular pattern (**Top, Bottom, Right, and Left**). These coils do not physically move.
*   **The Rotor (Moving Part):** A metallic ring holding bars  located at the center, surrounding the stator. The fan blades are bolted directly to this rotor. it has no current connection, due to stator magnetic field change, current induce and opposite magnetic poles/field created with respect to stator.
*   **The Capacitor:** A small electrical component wired in series with only one set of the stator coils (the Right/Left track).auxilary track

---

## ⚡ 2. Step-by-Step Working Mechanism

### Step 1: Splitting the Electrical Track
When you flip the fan switch, single-phase AC electricity from the wall enters the motor and splits into two paths:
1.  **Main Track:** Flows instantly to the **Top and Bottom** coils.
2.  **Auxiliary Track:** Flows to the **Right and Left** coils, but must pass through the **Capacitor** first.

### Step 2: The Capacitor's Charging Delay
Because AC current constantly reverses direction, the capacitor must continuously charge and discharge. 
*   It takes physical time for the capacitor to absorb electrons and build up electrical pressure (**Voltage**).
*   Because the capacitor is busy charging, it introduces a **90-degree timing delay** (phase shift), holding back both the voltage and the **current** on the Right/Left track.

### Step 3: Current Drives the Magnetic Field
Electric current flowing through a coil is solely responsible for creating its magnetic field. 
*   **Top/Bottom Coils:** Receive an instant push $\rightarrow$ create an **instant magnetic field**.
*   **Right/Left Coils:** Receive a delayed push $\rightarrow$ create a **delayed magnetic field**.

### Step 4: Creating the Shifting Magnetic Poles
Because of the capacitor's 90-degree delay, the magnetic poles do not turn on and off at the exact same millisecond. Instead, the North and South poles fire as a pair in a strict, clockwise sequence:
1.  **Top** becomes North / **Bottom** becomes South.
2.  A split-second later, **Right** becomes North / **Left** becomes South.
3.  Next, **Bottom** becomes North / **Top** becomes South.
4.  Finally, **Left** becomes North / **Right** becomes South.

*Net Result:* Even though the individual coils are stationary, the **magnetic field actively rotates in a smooth circle** (similar to a stadium wave).

### Step 5: Wireless Induction in the Rotor
The rotor at the center is completely wireless and has no direct electrical connection.
*   As the stator's magnetic field spins rapidly in a circle, it physically cuts through the metal bars of the rotor.
*   This moving magnetic field induces a **wireless electric current** inside the rotor.

### Step 6: The Eternal Magnetic Chase
*   The induced current inside the rotor creates its own **opposite magnetic pole** (South pole).
*   The rotor's South pole locks onto the stator's running North pole. 
*   Because the stator's field is constantly spinning electronically, the rotor is forced to **physically chase it** to align itself.
*   Since the fan blades are bolted to the rotor, they spin continuously right along with it.

---

## ⚠️ 3. Troubleshooting: Why Fans Get Stuck
If a capacitor becomes extremely weak or completely dies, the 90-degree timing delay vanishes. The Top/Bottom and Right/Left coils fire at the exact same time, causing the magnetic field to merely pulse straight up and down instead of rotating. 

The rotor gets pulled equally from all sides, causing the fan to **hum loudly and lock up**. Giving the blades a physical push breaks this magnetic deadlock, allowing the rotor's momentum to carry it past the dead zones so it can continue running on its own.
