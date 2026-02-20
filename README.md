# Experiment  Create-a-datacenter-with-two-hosts-and-run-two-cloudlets-on-it.
Create a datacenter with two hosts and run two cloudlets on it. The cloudlets run in VMswith Different MIPS requirements. The cloudlets will take different time to complete the execution Depending on the requested VM performance.
 
## Overview
This project demonstrates a CloudSim 3.0.3 simulation experiment where two cloudlets are executed on virtual machines with different MIPS values.

Since the virtual machines have different computational capacities, the cloudlets complete execution at different times depending on VM performance.

This experiment is commonly used in cloud computing laboratory exercises, academic coursework, and performance analysis studies.

---

## Aim
To create a datacenter with two hosts and execute two cloudlets on virtual machines having different MIPS requirements such that cloudlets take different execution times.

---

## Objectives
- To simulate a cloud datacenter using CloudSim
- To create multiple hosts within a datacenter
- To configure virtual machines with different MIPS values
- To execute cloudlets with identical workloads
- To analyze execution time differences

---

## Tools and Technologies

| Tool | Version |
|------|---------|
| Java JDK | 1.8 |
| CloudSim | 3.0.3 |
| IDE | IntelliJ IDEA / Eclipse |
| Operating System | Windows / Linux |

---

## System Configuration

### Datacenter Configuration

| Parameter | Value |
|------------|-------|
| Datacenters | 1 |
| Hosts | 2 |
| RAM | 4096 MB |
| Storage | 1,000,000 MB |
| Bandwidth | 10,000 Mbps |
| VM Scheduler | Time Shared |

---

### Virtual Machine Configuration

| Parameter | VM1 | VM2 |
|------------|------|------|
| MIPS | 500 | 2000 |
| RAM | 512 MB | 512 MB |
| Bandwidth | 1000 Mbps | 1000 Mbps |
| VMM | Xen | Xen |
| Scheduler | Time Shared | Time Shared |

---

### Cloudlet Configuration

| Parameter | Value |
|------------|--------|
| Cloudlets | 2 |
| Length | 40,000 MI |
| File Size | 300 MB |
| Output Size | 300 MB |
| Processing Elements | 1 |

---

## Program File

---

## Algorithm

1. Initialize the CloudSim library.
2. Create a datacenter with two hosts.
3. Configure host resources.
4. Create a datacenter broker.
5. Create two virtual machines with different MIPS values.
6. Submit the VM list to the broker.
7. Create two cloudlets with identical workloads.
8. Assign cloudlets to VMs.
9. Start the CloudSim simulation.
10. Collect execution results and stop the simulation.

---

## Execution Time Formula

Execution Time = Cloudlet Length / VM MIPS

---

## Sample Output


---

## Result

The experiment successfully demonstrates that cloudlets executed on higher MIPS virtual machines complete faster than those executed on lower MIPS VMs, even when the workload is identical.
![WhatsApp Image 2026-02-20 at 10 20 28 AM](https://github.com/user-attachments/assets/0acc2650-7027-4bad-a409-f5a66ab7f521)

---

## Conclusion

This simulation validates that CloudSim scheduling accurately reflects performance differences in heterogeneous cloud environments. Higher MIPS virtual machines reduce execution time for identical workloads.




