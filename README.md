# Customizable Graphs for Node-RED

This project provides a **set of Node-RED dashboard flows** that demonstrate how to create and customize interactive, real-time charts — including **multi-series graphs, filled-area charts, and time-based visualizations.**

It shows how to dynamically configure chart options such as:
- Axis titles and label formatting  
- Colors and line styles  
- Multi-series overlays (e.g., Voltage, Current, Power)  
- Live data generation with random values  
- Customizable chart updates every second  

The flow is designed for users who want to **fully control the appearance and behavior of Node-RED `ui_chart` components** directly from Function nodes.

---

## Video Tutorial

Watch the full explanation and demo on YouTube:  
[**Customizable Graphs for Node-RED**](https://youtu.be/zoGizM_zNV8)

---

## How It Works

The flow includes several Function nodes that:
1. Generate random test data for variables like *Power*, *Voltage*, and *Current*  
2. Format the data and `ui_control` properties dynamically  
3. Feed the data into Node-RED Dashboard `ui_chart` widgets  

You can easily modify:
- Chart type (`line`, `bar`, etc.)  
- Axis names and colors  
- Update frequency (set by the **inject** node)  
- Number of displayed points or buffer size  

---

## Installation

1. Open your **Node-RED editor**  
2. Click the **menu → Import → Clipboard**  
3. Paste the JSON flow from this repository  
4. Deploy and open your Node-RED Dashboard  
5. Enjoy your fully customizable real-time charts!  

---

## Features Demonstrated

| Feature | Description |
|----------|-------------|
| **Dynamic axis labels** | Automatically labeled X (Power) and Y (Voltage) axes |
| **Real-time updates** | Data refreshed every second |
| **Multiple chart types** | Normal line, filled line, and multi-series |
| **Custom color schemes** | Easily modify color palettes via the function node |
| **Time-series visualization** | Uses timestamps for live monitoring charts |

---

