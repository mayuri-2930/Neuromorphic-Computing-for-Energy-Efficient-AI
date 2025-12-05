# Neuromorphic Computing for Energy-Efficient AI

Neuromorphic Computing for Energy-Efficient AI is a comparative project that demonstrates how **Spiking Neural Networks (SNNs)** can drastically reduce power consumption compared to traditional **Feedforward Neural Networks (FFNNs)**, especially on low-power hardware like the Raspberry Pi 3B+. The project features a command-line interface (CLI) Python tool that benchmarks both models in terms of accuracy and energy usage.

---

## 👨‍💻 Team Members

**[Amir Shaikh](https://github.com/amir-200)**

* Email: [shaikhamir2888@gmail.com](mailto:shaikhamir2888@gmail.com)

**Arsh Sakaria**

* Email: 

**Divye Sharma**

* Email: 

**[Mayuri Sonawane](github.com/mayuri-2930)**

* Email: [mayu.112308@gmail.com](mailto:mayu.112308@gmail.com)



---

## 📊 PPT

[Click here to view the presentation](https://www.canva.com/design/DAGpkeBFiho/hyPolvrow8BxJ12pO6jHpg/view?utm_content=DAGpkeBFiho&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h42886e9712)

---

## 🌐 Overview

As Artificial Intelligence evolves, its deployment in edge devices and low-power systems poses a significant energy efficiency challenge. Traditional models like FFNNs are computationally intensive and unsuitable for environments like Raspberry Pi-based systems.

**Neuromorphic computing**, inspired by the brain's architecture, introduces **Spiking Neural Networks (SNNs)** that only consume energy during signal spikes—making them ideal for energy-constrained platforms.

This project compares the performance and energy efficiency of FFNNs and SNNs by implementing both on a Raspberry Pi 3B+. The Python CLI application provides metrics on inference accuracy and power consumption.

---

## 🎯 Objectives

* 🔍 Compare performance and energy usage of FFNN vs. SNN.
* 🔋 Demonstrate SNNs’ suitability for low-power AI.
* 🌐 Highlight real-world applications in edge computing and IoT.

---

## 🔍 Problem Statement

As AI systems scale, energy demands rise—especially when used on embedded or edge devices. FFNNs require constant computation, making them power-hungry. In contrast, **SNNs operate asynchronously**, consuming energy only when neurons fire. The project addresses whether SNNs can be a viable solution for low-power applications.

---

## 🚀 Key Features

* 📉 **Power Measurement**: Compare energy use of both models on hardware.
* 📈 **Accuracy Benchmarking**: Output accuracy for each model after inference.
* 🧠 **Neuromorphic Design**: Implement SNN using Python libraries like `Brian2`.
* 💻 **Hardware-Ready**: Optimized for Raspberry Pi 3B+.
* 🔧 **CLI Tool**: No GUI, lightweight script execution for benchmarking.

---

## 📌 Technologies Used

* **Languages**: Python
* **Libraries & Tools**:

  * `Brian2`, `BindsNET` - For simulating SNN
  * `NumPy`, `Pandas` - For data handling
  * `Matplotlib`, `Seaborn` - For visualizations
  * `Loihi SDK`, `SpiNNaker` *(for extended simulation, optional)*

---

## 🧪 Results

| Model Type | Accuracy | Power Consumption             |
| ---------- | -------- | ----------------------------- |
| FFNN       | \~95%    | High                          |
| SNN        | \~92%    | **\~220,000x more efficient** |

> ⚠️ SNNs show minor trade-offs in accuracy but offer **massive gains in power efficiency**, making them perfect for IoT and mobile environments.

---

## 🏛️ Societal Impact

* 🌍 *Sustainability*: Lower power consumption reduces carbon footprint.
* 🏥 *Healthcare*: Ideal for smart wearables and real-time diagnostics.
* 🏙️ *Smart Cities*: Enables energy-efficient traffic and home automation.
* ♿ *Inclusion*: Can power assistive technologies for people with disabilities.

---

## 🧠 Technical Skills Required

* Python Programming
* Neural Networks (FFNNs & SNNs)
* Raspberry Pi / Edge Hardware
* Neuromorphic Libraries like Brian2
* Data Analytics & Power Profiling

---

## ⚙️ How to Run


Clone the repo:
git clone https://github.com/<your-org>/Neuromorphic-AI.git
cd Neuromorphic-AI

Train FFNN:
python train/train_ffnn.py

Train SNN:
python train/train_snn.py

Compare Results:
Logs are saved in results/logs.csv or printed directly to console.

---

## 📚 References

* Maass, W. (1997). *Networks of Spiking Neurons*
* Davies et al. (2018). *Intel Loihi Chip*
* Merolla et al. (2014). *IBM TrueNorth*
* Roy, K., Jaiswal, A., Panda, P. (2019). *Neuromorphic Intelligence*
* [Intel Loihi Research](https://research.intel.com/loihi)
* [SpiNNaker Project](https://spinnakermanchester.github.io)

---
