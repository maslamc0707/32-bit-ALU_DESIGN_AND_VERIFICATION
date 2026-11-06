# 32-bit-ALU_DESIGN_AND_VERIFICATION


# 1. 📖Project Overview

This project focuses on the design and functional verification of a 32-bit Arithmetic Logic Unit (ALU).

The ALU is designed using Verilog HDL, and its functionality is verified using a UVM-based verification environment.

The verification environment is developed to validate the correctness of arithmetic and logical operations using directed testing, constrained-random stimulus, a self-checking scoreboard, functional coverage, and assertion-based verification.

# 2. 🎯Project Objectives

- Design a 32-bit ALU using Verilog HDL.
- Implement arithmetic and logical operations.
- Develop a structured UVM verification environment.
- Verify the functional correctness of the ALU.
- Implement a self-checking scoreboard.
- Apply functional coverage to measure verification progress.
- Use assertions to check important design behaviors.
- Achieve 100% functional coverage.

# 3. ⚙️ALU Features

- 32-bit input operands.
- 32-bit ALU result.
- Arithmetic and logical operations.
- Verilog-based RTL design.
- UVM-based functional verification.
- Self-checking verification environment.

# 4. 🔢Supported ALU Operations

## Operation
- AND:       Performs bitwise AND operation
- OR:        Performs bitwise OR operation
- XOR:       Performs bitwise XOR operation
- NOR:       Performs bitwise NOR operation
- ADD:       Performs addition of two operands
- SUB:       Performs subtraction of two operands

# 5. 🏗️UVM Verification Architecture
   
<img width="724" height="1024" alt="1793967238797-20929297-8112-4f21-883c-2cd73b853a89_1" src="https://github.com/user-attachments/assets/abbbc627-5437-4ec6-a7aa-4d0bbca4c56a" />


The ALU is verified using a structured UVM testbench.

## UVM Components
- Transaction: Defines ALU input and output transaction fields
- Sequence: Generates stimulus for the ALU
- Sequencer: Controls the flow of transactions
- Driver: Drives input stimulus to the DUT
- Monitor: Observes DUT input and output signals
- Agent: Contains the driver, sequencer, and monitor
- Environment: Instantiates and connects verification components
- Scoreboard: Compares expected and actual ALU results
- Test: Configures and executes the verification environment

# 6. 🔍Verification Methodology

The following verification methodology is used:

1. Develop the ALU RTL using Verilog HDL.
2. Create a UVM-based testbench.
3. Generate directed test scenarios.
4. Generate constrained-random input transactions.
5. Drive transactions to the ALU DUT.
6. Monitor DUT input and output signals.
7. Calculate expected results in the scoreboard.
8. Compare expected and actual results.
9. Collect functional coverage.
10. Check important design properties using assertions.

# 7. 📋Verification Scenarios

The following scenarios are considered during verification:

- Verification of all supported ALU operations.
- Verification using different input operand values.
- Verification with zero operands.
- Verification with maximum and minimum operand values.
- Verification using directed test cases.
- Verification using constrained-random stimulus.
- Verification of correct ALU result generation.

# 8. 📊Functional Coverage

Functional coverage is used to measure the verification progress and identify untested scenarios.

The coverage model focuses on:

- ALU operation coverage.
- Input operand coverage.
- Boundary value coverage.
- Zero and non-zero result scenarios.
- Different ALU control signal combinations.

Functional coverage helps evaluate the completeness of the verification process.

# 9. 🛡️Assertion-Based Verification

Assertions are used to check important design properties and verify expected ALU behavior.

SystemVerilog Assertions (SVA) are used in the verification environment to detect functional errors and ensure that the DUT behaves according to the expected specification.

# 10. 🛠️Tools and Technologies
```
Tool / Technology                        Purpose
Verilog HDL                              RTL Design
UVM                                      Functional Verification Methodology
QuestaSim                                Simulation and Debugging
Synopsys VCS                             Simulation
Functional Coverage                      Verification Progress Analysis
Assertions                               Design Behavior Checking
```
# 11. ✅Verification Results

The 32-bit ALU was successfully verified using a UVM-based verification environment.

Functional Coverage Results

Coverage Metric| Result
Functional Coverage| **100%**
Verification Status| **Passed**

**Key Achievements**

- Achieved **100% Functional Coverage**.
- Verified all implemented ALU operations.
- Implemented a self-checking scoreboard.
- Used UVM-based stimulus generation.
- Performed assertion-based verification.
- Validated the functional correctness of the ALU.

The verification results demonstrate that all defined functional coverage points and bins were successfully exercised during simulation.

# 12. 📝Project Summary

This project demonstrates the design and functional verification of a 32-bit Arithmetic Logic Unit using Verilog HDL and UVM.

A structured UVM verification environment was developed to verify the functional correctness of the ALU operations.

The verification process includes stimulus generation, transaction driving, signal monitoring, scoreboard-based checking, functional coverage collection, and assertion-based verification.

The project achieved 100% functional coverage, demonstrating that all defined functional coverage points were exercised during simulation.

This project provided practical experience in RTL design, UVM testbench architecture, functional verification, coverage analysis, and simulation-based debugging.

# 13. 🚀Future Improvements

The project can be extended with the following improvements:

- Add additional ALU operations such as multiplication and division.
- Improve constrained-random stimulus generation.
- Expand functional coverage to include additional corner cases.
- Add more SystemVerilog Assertions for design properties.
- Improve scoreboard checking for additional scenarios.
- Perform code coverage analysis.
- Integrate the verification environment into a regression testing flow.
- Explore formal verification techniques for selected ALU properties.

# 14. 💡Learning Outcomes

Through this project, I gained practical experience in:

- Verilog RTL Design.
- UVM-based Functional Verification.
- UVM Testbench Architecture.
- Transaction-Based Stimulus Generation.
- Scoreboard Implementation.
- Functional Coverage Modeling.
- Assertion-Based Verification.
- Simulation and Waveform Debugging.

# Author
## Mo. Aslam Chaudhary
Electronics and Communication Engineer
- Focus: VLSI Design and Verification
