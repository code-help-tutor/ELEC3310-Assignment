# ELEC3310 Assignment

**LAB**: 2 ELEC3310

**THE UNIVERSITY OF QUEENSLAND**

**School of Electrical Engineering and Computer Science**

**Induction Machine Experiment**

## 1. Aim
To determine the equivalent circuit parameters and analyze the characteristics of an induction motor.

## 2. Introduction
In this experiment, you will be examining the characteristics of an induction machines. As such, this “lab” or experiment will concentrate on your analysis of the results that provided for you. You will be required to write individual reports on your analysis of the results you obtain. Write the report based on the experimental data provided.

Because you are not confined to the laboratory during these experiments, this practical sheet will not give you any background theory regarding AC machine behavior. Instead, when analyzing the data to submit your report, you can access your usual study materials for the course (i.e. lecture notes and textbook) to examine and explain the data.

The AC machine which you will be testing can be seen in Figure 1 below. Physical step of these Machines is available in 50 - S104 and you are encouraged to talk to Tutors to organize a visit to the lab to look at the Machines. What you are looking at in Figure 1 is two induction machines. The shafts of both machines are mechanically coupled together. The purpose of having two induction machines in this experiment is for one to be the machine under test, and the other to provide opposing torque. More details regarding the specific role of the induction motor in the tests will be discussed at each experimental stage.

Both induction motors are rated at 5.5kW, the three phase windings are connected in star configuration. When the motor delivers rated power output, if it connected to a 660V (VLL) voltage, it will draw 6.2A at 0.886 lagging power factor. If the supplied frequency is 50 Hz, its full load mechanical speed is 1460 r.p.m. These data referes to the machine name plate data. However, you should follow the measurement data for finding out applied voltages and currents drawn.

**LAB**: 2 ELEC3310

**Figure 1 – Two induction machines.**

## 3. Experiments and Results

### 3.1 Locked rotor test
The locked rotor test is used to calculate the equivalent rotor and stator impedances of an induction motor. When the rotor is stationary, the slip is equal to 1, therefore the equivalent rotor resistance is low. Because the equivalent rotor resistance is low, the relatively high impedance magnetizing branch in the equivalent circuit can be neglected. Therefore, the information received from the locked rotor test gives information on solely the rotor and stator impedances of the induction motor under test.

The data retrieved from this test will be the line - to - line voltage, line current, motor speed (in rpm) and power factor of the machine under test.

In this experiment, there is no fixed mechanical locking mechanism to hold the rotor in place. Rather, the shafts of both the variable speed drive (VSD) controlled induction motor and the direct on - line machine under test (MUT) are mechanically coupled together. The VSD induction motor is speed controlled to 0 rpm. Therefore, when the MUT is connected to the AC supply, the VSD induction machine will supply counteracting torque to ensure that the coupled shaft speed remains at 0 rpm, which is equivalent to a locked rotor. The machine under test induction motor is connected to the mains 415V (line to line) three phase supply via three single phase 240 / 28.9V toroidal transformers. This step - down voltage ensures that close to rated current flows during the locked rotor test.

Locked rotor test results are given in Table 1.

**LAB**: 2 ELEC3310

**TABLE 1: Locked Rotor Results**
| Experiment Information | |
| ---- | ---- |
| Timestamp | Mon 29 Aug 2022 10:04:55 AM |
| Experiment Id | 49629 |
| Unit Id | 4 |
| Experiment Specification | |
| Setup Name | Locked Rotor |
| Experiment Results | |
| Ph - Ph Voltage (Volts) | 425.4 |
| Phase Current (Amps) | 0.77 |
| Power Factor | 0.518 |
| Motor Speed (RPM) | 0 |

Important to note: The current and voltages measured in this test are taken from the primary side of the step - down transformer. These values must be converted to the secondary side of the transformer to use as data for the locked rotor test.

The test is performed at rated frequency.

Use these results to answer the following questions:

#### 3.1.1. The line - to - line voltage on the secondary side of the step down transformer is 50V. In what configuration are the three phase torodial transformers connected (i.e. star - star, delta - delta, star - delta or delta - star)?
#### 3.1.2. What is the real power consumed in the locked rotor test?
#### 3.1.3. What parameters of the induction machine equivalent circuit are being assessed in this test?
#### 3.2.3. Use the test results to determine the equivalent impedance, resistance and reactance of the locked rotor test.

### 3.2 No load test
The no load test is used to gather information about the magnetizing branch in the induction machine equivalent circuit. When an induction motor is unloaded, the shaft will be running at practically synchronous speed (not quite however, as if it were running at synchronous speed no currents would be induced in the rotor windings) and therefore a very small, practically zero slip. This causes the equivalent rotor impedance to be very large. Therefore, the rotor can be considered to be an open circuit in this test, and the data obtained from this test will give information on the stator and magnetizing impedance.

The data retrieved from this test will be the line - to - line voltage, line current (equal to phase current as star connected), motor speed (in rpm) and power factor of the machine under test.

No load test Results are given in Table 2.

**LAB**: 2 ELEC3310

**TABLE 2: No Load Test Results**
| Experiment Information | |
| ---- | ---- |
| Timestamp | Mon 29 Aug 2022 9:57:30 AM |
| Experiment Id | 49625 |
| Unit Id | 3 |
| Experiment Specification | |
| Setup Name | No Load |
| Experiment Results | |
| Ph - Ph Voltage (Volts) | 423.6 |
| Phase Current (Amps) | 6.62 |
| Power Factor | 0.121 |
| Motor Speed (RPM) | - 1499 |

The three phase transformer bank mentioned in the locked rotor test has been switched out in this experiment, therefore measured voltages and currents do not need to be converted or adjusted.

#### 3.2.1. What is the real power consumed in the no load test?
#### 3.2.2. What parameters of the induction machine equivalent circuit are being assessed in this test?
#### 3.2.3. Use test results to determine the equivalent impedance, resistance and reactance of the no load test.
#### 3.2.4. How many poles does this induction machine have? Explain how you find it?
#### 3.2.5. Determine the slip?
#### 3.2.6. By what method could the stator resistance be determined?
#### 3.2.7. Assume the stator resistance (R1) of the machine under test is 0.988 Ω / phase. Using the results from sections 3.2 and 3.3, determine the full equivalent circuit of the induction machine under test. Consider that stator and rotor reactance are equal.
#### 3.2.8. Determine rotational losses?

### 3.3 Full load test
This experiment will give information regarding the behavior of the MUT induction machine under full load conditions. In this experiment, rather than having a separate mechanical load for the MUT induction machine, the VSD controlled induction machine will act as a mechanical load. The VSD induction machine will act in torque control mode to ensure that a counteracting full load torque is applied to the MUT induction motor.

The data retrieved from this test will be the line - to - line voltage, line current (equal to phase current as star connected), motor speed (in rpm) and power factor of the machine under test.

Full load and synchronous speed results are given in Tables 3 and 4 Respectively.

**TABLE 3: Full Load Test Results**
| Experiment Information | |
| ---- | ---- |
| Timestamp | Mon 29 Aug 2022 10:01:26 AM |
| Experiment Id | 49627 |
| Unit Id | 2 |
| Experiment Specification | |
| Setup Name | Full Load |
| Experiment Results | |
| Ph - Ph Voltage (Volts) | 422 |
| Phase Current (Amps) | 12.87 |
| Power Factor | 0.833 |
| Motor Speed (RPM) | - 1475 |

**TABLE 4: Synchronous Speed Results**
| Experiment Information | |
| ---- | ---- |
| Timestamp | Mon 29 Aug 2022 10:06:40 AM |
| Experiment Id | 49630 |
| Unit Id | 2 |
| Experiment Specification | |
| Setup Name | Synchronous Speed |
| Experiment Results | |
| Ph - Ph Voltage (Volts) | 424.3 |
| Phase Current (Amps) | 0.82 |
| Power Factor | 0.676 |
| Motor Speed (RPM) | 1499 |

The three phase transformer bank mentioned in the locked rotor test has been switched out in this experiment, therefore measured voltages and currents do not need to be converted or adjusted.

#### 3.3.1. What is the real power being delivered to the machine in this test?
#### 3.3.2. What is the reactive power being delivered to the machine in this test?
#### 3.3.3. Using the cantilever (approximate) equivalent circuit, determine the output power delivered by the MUT induction machine.
#### 3.3.4. What is the machine efficiency?
#### 3.3.5. Determine the electrical and mechanical torque.

Your report should include a cover page, including your details, i.e., name and ID, and answer to those questions with discussion.# ELEC3310 Assignment

# CS Tutor | 计算机编程辅导 | Code Help | Programming Help

# WeChat: cstutorcs

# Email: tutorcs@163.com

# QQ: 749389476

# 非中介, 直接联系程序员本人
