# I2C_MASTER_TOP
ASIC Implementation of I2C_MASTER_TOP using OpenLane &amp; Sky130
# I2C_MASTER_TOP – ASIC Implementation with OpenLane

## 📌 Project Description
This project presents the ASIC implementation of the `I2C_MASTER_TOP` module using the OpenLane physical design flow and the Sky130 PDK.

The original RTL source was obtained from an open-source GitHub repository. Using OpenLane, we performed the complete digital ASIC design flow including:

- Synthesis  
- Floorplanning  
- Placement  
- Clock Tree Synthesis (CTS)  
- Routing  
- DRC/LVS checks  
- GDSII generation

The final outputs (GDS, DEF, LEF, netlist, and layout views) are included in this repository.

## 🔗 Source of RTL
The Verilog source code for the `I2C_MASTER_TOP` module was originally taken from the following open-source repository:

**https://github.com/freecores/i2c**

We used only the top-level module (`i2c_master_top.v`) in our implementation.

## 📂 Project Structure

