# LECTURE05-Control-of-Grid-Connected-Converters

In this unit the student must learn: <br>
* Typical control loops for controlling active and reactive power.<br>
* Classification of grid forming, grid feeding, grid supporting converters.<br><br>

Lecture 05 can be found [here](https://github.com/IEE3311-EDP-ERRI/LECTURE05-Control-of-Grid-Connected-Converters/blob/main/5_Grid_Connected_Converters.pdf)<br><br>

In addition read the following material in this order:
* Fundamentals P, Q Control loops [here](https://github.com/IEE3311-EDP-ERRI/LECTURE05-Control-of-Grid-Connected-Converters/blob/main/2006%20Overview%20of%20Control%20and%20Grid%20Synchronization%20for%20Distributed%20Power%20Generation%20Systems.pdf)<br>
Summary:<br>
    * Control of P,Q in Synchronous Rotating (dq) and Stationary frames (alfa-beta).
    * Understanding the decoupling terms in dq frame.
    * Control structure for harmonics compensation.
    * Control under unbalanced networks (or faults), i.e. voltage unbalanced:
        *  Keep current balanced and power will have oscillations.
        *  Kepp P, or Q constant and current will be unbalanced.
        *  The previous is achieved using sequence separation (positive, negative).<br>
 Important Sections:<br>
     * I, II, II (general knowledge)
     * IVa, IVb Control Structure.
     * IVc never used in real life, not that important. But good to know.
     * Va (used only when low number of harmonics are copensated). Vb (used when low or high numbers of harmonics are compensated)
     * VIb,c,d. Use of sequence separation for controlling P, Q under unbalanced networks.
      
* Grid Connected converters classification and control  [here](https://github.com/IEE3311-EDP-ERRI/LECTURE05-Control-of-Grid-Connected-Converters/blob/main/2012_Control_of_Power_Converters_in_AC_Microgrids.pdf)<br>
    * Classification of converters connected as voltage source with low impedance series or current source with high impedance parallel.
    * Definition of grid Forming, grid feeding  and grid supporting converters.
    * Introduction of grid supporting acting voltage source (no PLL for tracking an angle from the grid voltage) or current source (with PLL for tracking an angle from the grid voltage)
    * Importance of the dependance of grid voltage and grid frequency on active and reactive power.
    * Frequency and voltage Droop curves
    * Primary, secondary and tertiary control layers in a microgrid.

 * [Review of grid Connected Converters](https://github.com/IEE3311-EDP-ERRI/LECTURE05-Control-of-Grid-Connected-Converters/blob/main/2021%20Grid-Forming%20Converters%20Control%20Approaches%2C%20Grid-Synchronization%2C%20and%20Future%20Trends—A%20Review.pdf)<br>
    *  Extention of Grid Forming concept when converters connect to tranmission networks.
    *  General structures for Grid Forming control. 

  
* Modern Grid Forming converters [here](https://github.com/IEE3311-EDP-ERRI/LECTURE05-Control-of-Grid-Connected-Converters/blob/main/2025%20Grid-Supporting%20Renewable%20Energy%20Systems%20With%20Power%20Electronics%20Interfaces.pdf)<br>

Complementary read:<br>
[Control of Grid Connected Converters](https://github.com/IEE3311-EDP-ERRI/LECTURE05-Control-of-Grid-Connected-Converters/blob/main/2010%20Power-Synchronization%20Control%20of%20Grid-Connected%20Voltage-Source%20Converters.pdf)<br>
