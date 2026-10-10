# AI Viral Shorts Generator 🚀

Transform one video into five short-form video clips with a Python-powered video repurposing tool.

AI Viral Shorts Generator uses a virality-based clip selection matrix to identify potentially engaging moments in a source video and generate short clips for platforms such as YouTube Shorts and Instagram Reels.

## ✨ Features

- **Generate 5 Shorts:** Create five short clips from a single source video.
- **Virality-Based Selection:** Select candidate moments using a clip-selection matrix.
- **Automated Workflow:** Reduce manual effort involved in finding and extracting highlights.
- **Kaggle Support:** Run the notebook in Kaggle's cloud computing environment.
- **Content Repurposing:** Suitable for podcasts, interviews, educational videos, and other supported content.

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Kaggle Notebooks
- GPU acceleration, where supported by the implementation

## 📋 Requirements

- A Kaggle account
- The project notebook (`.ipynb`)
- Internet access if required for video downloading or dependency installation
- GPU access if required by the notebook's processing workflow
- Required Python packages listed in `requirements.txt`, if provided

## 🚀 Getting Started

### Option 1: Run on Kaggle

1. Sign in to [Kaggle](https://www.kaggle.com/).
2. Open [Kaggle Notebooks](https://www.kaggle.com/code).
3. Import `notebooks/ai_viral_shorts_generator.ipynb`.
4. Enable GPU acceleration if needed and available.
5. Enable internet access if required.
6. Run the notebook cells in order.
7. Enter a supported source video URL in the designated input cell.
8. Execute the generation workflow.
9. Find the generated videos in the configured output directory.

### Option 2: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-viral-shorts-generator.git
cd ai-viral-shorts-generator
```

Install the dependencies if a `requirements.txt` file is included:

```bash
pip install -r requirements.txt
```

Follow the notebook instructions to run the project.

## 📁 Project Structure

```text
ai-viral-shorts-generator/
├── README.md
├── requirements.txt
├── notebooks/
│   └── ai_viral_shorts_generator.ipynb
├── docs/
│   └── kaggle_setup_guide.txt
├── src/
├── assets/
└── outputs/
```

## 🎯 Use Cases

- YouTube content creation
- Podcast clip generation
- Social media content repurposing
- Affiliate marketing content workflows
- Educational video highlights
- Short-form video production

## ⚠️ Limitations

- Generated clips may require manual review or additional editing.
- Processing speed depends on video length, available resources, and implementation details.
- The selection matrix does not guarantee viral performance, views, or revenue.
- Platform availability, download restrictions, and copyright requirements may affect which videos can be processed.

## ⚖️ Responsible Use

Use this tool only with videos you own or have permission to download, edit, and republish. Follow the terms of service of the source platform and the destination platforms.

## 📖 Documentation

See `docs/kaggle_setup_guide.txt` for instructions on setting up Kaggle, enabling GPU acceleration, running the notebook, and downloading generated clips.

## 🤝 Contributions

Suggestions, bug reports, and improvements are welcome. Please describe the issue and include relevant error messages when reporting a bug.

## 📄 License

The project's license and usage permissions should be specified in the `LICENSE` file. If this is a commercial digital product, confirm that your chosen license matches the permissions you intend to grant.

---

**One video. Five Shorts. A faster content workflow.**