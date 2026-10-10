AI Viral Shorts Generator 🚀
Turn one video into five short-form clips using a Python notebook running on Kaggle.
AI Viral Shorts Generator is a video-repurposing project that uses a virality-based clip-selection matrix to identify potentially engaging moments in a source video and generate five short clips.
The project is designed to run in Kaggle, so you can use its hosted notebook environment instead of setting up the entire workflow locally.
✨ Features
- Generate 5 Shorts: Create five short clips from one source video.
- Virality-Based Selection: Use a selection matrix to identify candidate moments.
- Automated Workflow: Reduce manual effort spent finding and extracting highlights.
- Kaggle Notebook: Run the workflow in Kaggle's hosted environment.
- Content Repurposing: Suitable for supported podcasts, interviews, educational videos, and other source content.
🧰 Project Structure
ai-viral-shorts-generator/
├── README.md
├── requirements.txt
├── kaggle_setup_guide.txt
└── notebook.ipynb
- README.md — Project overview and usage instructions.
- requirements.txt — Python dependencies used by the notebook.
- kaggle_setup_guide.txt — Instructions for setting up Kaggle, enabling a GPU, running the notebook, and downloading outputs.
- assets/ — Optional product banner and screenshots.
The working .ipynb notebook is hosted on Kaggle. Add your Kaggle notebook URL below so users can open it.
📋 Requirements
- A Kaggle account
- Access to the Kaggle notebook
- Internet access if required for downloading source videos or installing dependencies
- GPU access if required by the notebook and available on your Kaggle account
- The Python packages listed in requirements.txt
🚀 Getting Started
1. Open the Kaggle Notebook
Kaggle notebook: ADD_YOUR_KAGGLE_NOTEBOOK_URL_HERE
Open the link above after replacing the placeholder with your actual Kaggle notebook URL.
2. Configure the Notebook
1. Sign in to Kaggle.
2. Open the project notebook.
3. Enable GPU acceleration if required and available.
4. Enable internet access if the notebook needs it.
5. Run setup cells and then execute the notebook cells in order.
3. Generate Your Shorts
1. Find the input cell for the source video URL.
2. Enter a supported video link in the designated input field or variable.
3. Run the cells in the order specified by the notebook.
4. Wait for video processing and clip generation to finish.
5. Locate the generated clips in the output path configured by the notebook.
6. Download and review the clips before publishing.
For detailed instructions, read kaggle_setup_guide.txt.
📦 Dependencies
Install dependencies only if the notebook requires them and they are not already installed in your Kaggle session.
pip install -r requirements.txt
Some dependencies may require system tools such as FFmpeg or Node.js. Follow the notebook's setup cells and the included guide. Avoid reinstalling PyTorch or CUDA-related packages unless the project instructions specifically require it.
🎯 Use Cases
- YouTube Shorts creation
- Podcast highlights
- Social media content repurposing
- Affiliate marketing content workflows
- Educational video highlights
- Short-form video production
⚠️ Limitations
- Generated clips may require review or additional editing.
- Processing time depends on the source video, dependencies, and available Kaggle resources.
- GPU availability and usage quotas are controlled by Kaggle and may change.
- The selection matrix does not guarantee virality, views, followers, or revenue.
- Source-video availability and platform restrictions may affect processing.
⚖️ Responsible Use
Only download, edit, and republish videos you own or have permission to use. Follow the terms of service of the source platform and any platform where you publish the generated clips.
📖 Documentation
See [`kaggle_setup_guide.txt`](kaggle_setup_guide.txt) for setup, GPU configuration, notebook execution, and output-download instructions.
🤝 Contributions
Suggestions and bug reports are welcome. When reporting an issue, include the relevant error message and the step where it occurred. Do not include passwords, API keys, or other secrets.
📄 License and Usage
