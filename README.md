# About AI By AI Through AI

## Project Overview
This project aims to create a series of AI-generated animated videos focused on educating viewers about artificial intelligence. The content will be entirely generated by AI, covering topics such as how AI works, how to build AI systems, and the future of AI technologies.

## Objectives
- Generate high-quality animated videos using AI.
- Educate audiences about key concepts in AI and machine learning.
- Create engaging visual content that is informative and accessible.

## Project Structure
- `scripts/`: Contains Python scripts and code files for generating visuals and animations.
- `storyboards/`: Holds storyboards for each video segment.
- `assets/`: Stores generated images, audio files, and other media.
- `video/`: Contains the final video output.
- `prompts.txt`: A file with all the prompts used for generating visuals and any additional notes.

## Getting Started
To run this project, you need to set up Stable Diffusion and its dependencies. Follow the setup instructions in the project documentation.

## Acknowledgments
This project leverages open-source AI tools and resources. Special thanks to the contributors of Stable Diffusion and Automatic1111's WebUI for providing the necessary tools for this endeavor.

## Day 1: Setup and Preparation

1. **Set Up GitHub Repository**
   - Cloned the GitHub repo `AboutAI_ByAI_ThroughAI` to the local machine.
   - Created a directory structure for scripts, assets, storyboards, etc.

2. **Set Up Stable Diffusion with Automatic1111's WebUI**
   - Installed Python (3.10+) and Git.
   - Cloned the Automatic1111's WebUI repository:
     ```bash
     git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git
     cd stable-diffusion-webui
     ```
   - Downloaded the Stable Diffusion model file from Hugging Face and placed it in the appropriate folder.
   - Installed the required dependencies using:
     ```bash
     pip install -r requirements.txt
     ```
   - Ran the WebUI to ensure it's set up correctly:
     ```bash
     python webui.py
     ```

3. **Download LLaMA Model**
   - Accessed the LLaMA model through Hugging Face or Meta’s repository.
   - Installed necessary libraries if using Hugging Face (e.g., `transformers`).

4. **Set Up Prompt Generation with LLaMA**
   - Wrote a Python script to generate AI-related prompts using LLaMA.
   - Used relevant themes or questions to steer the prompt generation.

5. **Organize Project Files**
   - Created initial files or scripts in the GitHub repo to document the setup and progress.

6. **Document Progress**
   - Updated the README in the GitHub repository to reflect the tasks completed on Day 1 and any challenges faced.

