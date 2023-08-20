# TryOnAI

Try On AI refers to an application that allows users to virtually "try on" clothing, accessories, 
or other items using augmented reality (AR) or virtual reality (VR) technology. This project could involve creating a platform where users upload a photo of themselves, and the AI technology superimposes different clothing items onto their image to show how they might look when wearing those items. 
It's commonly used in the fashion and e-commerce industries to enhance the online shopping experience.


## Requirements

Before you get started, ensure you have the following prerequisites:

- **Python Environment**: Make sure you have Python installed on your system.

- **Stable Diffusion Inpaint**: Install Stable Diffusion Inpaint. Refer to its documentation or source repository for installation details.

- **Python Dependencies**: Install the required Python packages 
## Dependencies

This project relies on the following external libraries and models:
```bash
 https://github.com/Fantasy-Studio/Paint-by-Example
```

```bash
https://huggingface.co/Fantasy-Studio/Paint-by-Example
```



## How to Use

Follow these steps to use TryOnAI:

1. **Clone the Repository**: Clone the TryOnAI repository to your local machine.

   ```bash
   git clone https://github.com/your-username/tryon-ai.git
   ```

2. **Navigate to the Project Directory**: Enter the project directory.
    
   cd tryon-ai

**Prepare Input Image**: 
Prepare an image of yourself wearing basic clothing. Ensure it's clear and well-lit. Name it 'input.jpeg' and place it in the project directory.

**Run the TryOnAI Process**:
Execute the provided script to run TryOnAI. This script performs the following steps:
* Utilizes Stable Diffusion Inpainting and DreamBooth to superimpose clothing onto your input image.
* Generates a mask and refines the result.
* Outputs the final image with virtual clothing.

      python tryonai.py

**View and Save the Result**:

The result will be saved as 'result.png' in the project directory.
This image will display you wearing the selected virtual clothing.
Customize with Example Image (Optional):

You can further customize your virtual outfit by providing an 'example_image'. This image can be any clothing item you want to try on.
TryOnAI Web Interface (Optional):

If you prefer a user-friendly interface, TryOnAI offers a web-based interface for ease of use.
Run the following command to launch the interface:

```bash
python tryonai_interface.py


