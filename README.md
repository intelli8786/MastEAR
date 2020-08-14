
# Abstract
[![](https://user-images.githubusercontent.com/25438139/90119211-3efeb680-dd94-11ea-918f-72ddc255e9e8.PNG)](https://youtu.be/BveubkMsziM)
>*With the advent of the Fourth Industrial Revolution, we are reaping the benefits of numerous machinery. With the introduction of smart factories, machines are replacing more and more tasks, but there is a problem that maintenance and soundness management become exponentially difficult because more and more complex machines have more parameters. In order to solve this problem, we propose a system that analyzes the noise generated by the machine and observes the machine's failure or precursor symptoms in real time. Our approach was fueled by inspiration from the diagnostic and health management methods of experts who diagnose faults by analyzing the sounds produced by machines. The noise classification method in this system is based on the MLP model, and this project focuses on the Human-Computer Interaction (HCI) perspective. And the performance-focused project is based on the Inception v3 model and is published in [[CNNbasedPHM](https://github.com/intelli8786/CNNbasedPHM)]. Our approach diagnoses and notifies faults in real time, reducing human damage and economic loss due to sudden faults, and reducing maintenance and maintenance costs by reducing the total number of unnecessary diagnostics can be expected.*

# Usage
## Development Environment
* CPU : i7 8086k
* GPU : NVIDIA GeForce RTX2080ti
* Windows 10 1903
* Lattepanda DFR0547
* Dynamic mic
## Dependency
* dotnet framework 4.5.1
* MathConverter 1.2.1.1
* NAudio 1.8.2
* Newtonsoft.Json 10.0.3
* python 3.6
* jupyter 5.0.0
* tensorflow-gpu 1.9.0
* librosa 0.8.0
* numpy 1.16.1
* opencv 4.2.0


## Conception
![구상안](https://user-images.githubusercontent.com/25438139/90116468-7ff4cc00-dd90-11ea-94f5-221128da021c.png)

## Proposed system
### Management console
* It provides the function to monitor the whole system.
![ManagementConsole](https://user-images.githubusercontent.com/25438139/90116475-82572600-dd90-11ea-9e33-8e079fdbb859.png)

### Actuator console
* It provides the function of registering new machinery and learning sounds.
![ActuatorConsole](https://user-images.githubusercontent.com/25438139/90116471-8125f900-dd90-11ea-8788-12d85dfab7bc.png)

### Training console
* It provides a function to check learning results and to adjust parameters related to learning.
![TrainingConsole](https://user-images.githubusercontent.com/25438139/90116473-81be8f80-dd90-11ea-8ba0-ba8fb33fb702.png)