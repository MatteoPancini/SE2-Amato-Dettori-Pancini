# eMall – e-Mobility for All
Electric mobility (e-Mobility) is a way to limit the carbon footprint caused by our urban and sub-urban mobility needs. When using an electric vehicle, knowing where to charge the vehicle and carefully planning the charging process in such a way that it introduces minimal interference and constraints on our daily schedule is of paramount importance.
e-Mobility Service Providers (eMSPs) offer to end users the possibility to:
1) know about the charging stations nearby, their cost, any special offer they have; 2) book a charge in a specific charging station for a certain timeframe;
3) start the charging process at a certain station;
4) notify the user when the charging process is finished;
5) pay for the obtained service.
Charging stations are owned and managed by Charging Point Operators (CPOs). Each CPO has its own IT infrastructure administrated through the so-called Charge Point Management System (CPMS). The CPMS handles the acquisition of energy from external (3rd party) Distribution System Operators (DSOs) and distribute it to the connected vehicles, making decisions, such as the amount of energy to be used for each connected vehicle. CPOs can dynamically decide from which DSO to acquire energy, for instance, depending on the current price and/or on the used mix of energy sources and, based on these, can dynamically decide the cost of a charging and set special offers. If batteries are available at the charging station, a CPO can also decide whether to store or not energy and whether to use the energy available in the batteries instead of acquiring it from DSOs. These decisions can be handled either manually by human operators or automatically by CPMSs.
CPOs offer the following main functions through their CPMSs:
a) know the location and “external” status of a charging station (number of charging sockets
available, their type such as slow/fast/rapid, their cost, and, if all sockets of a certain type are occupied, the estimated amount of time until the first socket of that type is freed);
b) start charging a vehicle according to the amount of power supplied by the socket, and monitor the charging process to infer when the battery is full;
c) know the “internal” status of a charging station (amount of energy available in its batteries, if any, number of vehicles being charged and, for each charging vehicle, amount of power absorbed and time left to the end of the charge);
d) acquire by the DSOs information about the current price of energy;
e) decide from which DSO to acquire energy (if more than one is available);
f) dynamically decide where to get energy for charging (station battery, DSO, or a mix thereof according to availability and cost).
The interaction between the various providers (eMSPs, CPOs, and DSOs) occurs through uniform APIs. Thanks to this, an eMSP can interact with multiple CPOs and, on the other side, a CPO can interact with multiple eMSPs. Hence, users can exploit a large variety of charging options. Similarly, a CPO can interact with multiple DSOs and vice versa.

## 🎯 Goal and approach
The objective of this project is to apply in practice what you learn during lectures with the purpose of becoming familiar with software engineering practices and able to address new software engineering issues in a rigorous way. The project includes two assignments:
1. The preparation of a Requirement Analysis and Specification Document (RASD) for a problem we provide you.
2. The definition of the Design Document (DD) for the system considered in point 1 above.

## 👤 Team
+ Valeria Amato
+ Francesco Dettori
+ Matteo Pancini
