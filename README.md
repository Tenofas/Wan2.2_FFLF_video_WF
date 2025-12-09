# Wan2.2 FFLF video WF - ComfyUI Workflow

![Preview](assets/workflow.png)

## 📖 Description

This ComfyUI workflow leverages the WAN 2.2 model to generate extended video sequences through a multi-stage image-to-video approach. 
The workflow is designed to produce four consecutive video takes that can be seamlessly combined into a single 20-32 second final output.

## ✨ Features

- 4-Stage Sequential Generation: Creates four separate video takes (Take 1-4), each approximately 5-8 seconds in duration
- First & Last Frame Control: Each take supports optional first-frame and last-frame conditioning, allowing precise control over the beginning and end of each segment
- Image-to-Video Pipeline: Utilizes WAN 2.2's i2v capabilities with customizable positive and negative prompts for each take

## 🖼️ Examples

| Input/Prompt | Output |
|--------------|--------|
| ![Example 1](assets/example1.png) | ![Result 1](assets/result1.png) |
| ![Example 2](assets/example2.png) | ![Result 2](assets/result2.png) |

## 📋 Requirements

### Models Required
- [Model 1] - [link]
- [Model 2] - [link]

### Custom Nodes
- [Custom Node 1] - [Link al repo GitHub]
- [Custom Node 2] - [Link]
- [Custom Node 3] - [Link]

## 🚀 Installation

1. Download the workflow JSON file
2. Install required custom nodes via ComfyUI Manager
3. Download required models and place in ComfyUI folders
4. Load the JSON in ComfyUI

## 💡 Usage

1. **[Step 1]** - [Descrizione]
2. **[Step 2]** - [Descrizione]
3. **[Step 3]** - [Descrizione]
4. Click "Run" to generate

### Recommended Settings
- **Steps**: [X]
- **CFG Scale**: [X]
- **Sampler**: [Nome sampler]
- **Scheduler**: [Nome scheduler]

## 🤝 Support

- **Issues**: Open an issue on this repository
- **X (Twitter)**: [@tenofaz](https://x.com/tenofaz)
- **Website**: [tenofas.ai](https://tenofas.ai)

## ⭐ Credits

Workflow developed by **Tenofas**

If you find this workflow useful, consider:
- ⭐ Starring this repository
- 🔄 Sharing with the community
- 🐦 Following on [X](https://x.com/tenofaz)

---

*Part of the [Tenofas ComfyUI Workflows](https://github.com/Tenofas) collection*
