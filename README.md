# Control Editor IoTControl Examples

A community-driven collection of examples and templates for IoTControl.

## 🚀 Quick Start

### Browse Examples Online
Visit our [Examples Gallery](https://github.com/iotctrl/iotctrl-examples/) to preview all available examples.

### Load Examples in [Your App Name]
1. **Copy the raw URL** of any JSON file below
2. In Control Editor, use the "Load System" feature
3. Paste the URL and load the example

## 📂 Example Categories

### 🟢 Beginner
- [`SUM.json`](examples/level1/SUM.json) - Simple starting point
- [`SUB.json`](examples/level1/SUB.json) - Basic math example
- [`OpenLoop.json`](examples/level1/OpenLoop.json) - Servomechanism open loop diagram block

### 🔵 Intermediate  
- [`tfPI.json`](examples/level2/tfPI.json) - Transfer function implementing PI to control servomechanism
- [`tfPID_Simulation.json`](examples/level2/tfPID_Simulation.json) - Transfer function implementing PID to simulated system
- [`PID_Simulation.json`](examples/level2/PID_Simulation.json) - PID to simulated system
- [`Speed_Control_Prototype.json`](examples/level2/Speed_Control_Prototype.json) - PID to control servomechanism speed

### 🔴 Advanced
- [`PL.json`](examples/level3/PL.json) - Phase lead to control servomechanism
- [`MFC.json`](examples/level3/MFC.json) - Model-free to control servomechanism
- [`Hinf_FT_3or.json`](examples/level3/Hinf_FT_3or.json) - H-infinity control

## 🤝 Contributing

We love community contributions! Here's how you can help:

### Add Your Example
1. **Fork this repository**
2. **Add your JSON file** to the appropriate category folder
3. **Test your example** works in IoTControl
4. **Submit a Pull Request**

### Quick Add via GitHub Web
1. Click "Add file" → "Create new file"
2. Path: `examples/your-category/your-example-name.json`
3. Paste your JSON content
4. Create Pull Request

### Rate & Review Examples
- Use **GitHub Reactions** (👍 👎) on example files
- **Comment on Pull Requests** with feedback
- **Open Issues** for bug reports or suggestions

## 📋 Guidelines
- ✅ Ensure JSON is valid and loads correctly
- ✅ Use descriptive file names
- ✅ Include comments in JSON if helpful
- ✅ Test your example before submitting
- ✅ Follow the existing folder structure

## 🔗 Direct URLs for Loading

Copy these raw URLs to load directly in IoTControl:

```bash
# Beginner Examples
https://raw.githubusercontent.com/iotctrl/iotctrl-examples/examples/level1/OpenLoop.json

# Intermediate Examples  
https://raw.githubusercontent.com/iotctrl/iotctrl-examples/examples/level2/Speed_Control_Prototype.json

# Advanced Examples
https://raw.githubusercontent.com/iotctrl/iotctrl-examples/examples/level3/Hinf_FT_3or.json