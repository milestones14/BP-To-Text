# Unreal Blueprint Logic Parser

A simple HTML tool to convert Unreal Engine Blueprint text into a clean, readable logic tree.
I made this because I couldn't find any tools out there for free, mostly overpriced.

## 🚀 How to Use
1. **In Unreal Engine**: Select the nodes you want to document and press `Ctrl + C`.
2. **In the Parser**: Go to [the parser](https://milestones14.github.io/BP-To-Text/)
3. **Convert**: Click **"Generate Clean Logic Tree"**.
4. **Copy**: Grab the formatted pseudocode for use in your project documentation or for AI.

## ✨ Key Features
- **Recursive Data Resolution**: Automatically pulls values from "Pure" nodes (like Getters, Math, and Breaks) into the execution line.
- **Branch Support**: Correcty maps `IF/THEN/ELSE` flow from IfThenElse nodes.
- **T3D Hardened**: Specifically designed to handle Unreal's internal GUIDs and inconsistent link formatting.
- **Privacy Focused**: No data is ever sent to a server; all parsing happens locally in your browser.
