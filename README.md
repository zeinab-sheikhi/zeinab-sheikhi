```python
class Zeinab:
    @staticmethod
    def research() -> str:
        return "Machine Learning Researcher in AI for Biology"

    @staticmethod
    def skills() -> dict:
        return {
            "Programming Languages": ["Python", "Java", "Dart"],
            "Machine Learning & Deep Learning": [
                "PyTorch", "scikit-learn", "Hugging Face Transformers",
                "CNNs", "Transformers",
            ],
            "Generative & Agentic AI": ["MCP", "smolagents", "RAG", "vLLM"],
            "Data Analysis & Visualization": ["Pandas", "NumPy", "Seaborn"],
            "MLOps & Cloud": [
                "AWS (S3, SageMaker, ECR, ECS)", "Docker", "Apache Airflow",
                "GitHub Actions", "Terraform",
            ],
            "Backend Development": ["FastAPI", "Flask"],
            "Frontend Development": ["Flutter"],
        }

    @staticmethod
    def projects() -> dict:
        return {
            "BOTANIC1": {
                "description": (
                    "Fine-tuned a plant genomic language model to predict "
                    "chromatin accessibility (ATAC-seq). The fine-tuned model "
                    "outperformed a ChromBPNet baseline trained on the same species."
                ),
                "paper": "https://www.biorxiv.org/content/10.64898/2026.09.04.749355v1",
                "model": "https://huggingface.co/collections/living-models/botanic1",
            },
            "Archon": (
                "Developed a CNN-based model to detect genomic structural variants "
                "from short-read sequencing data. Improved F1-score from 0.31 "
                "for the best baseline to 0.66."
            ),
            "HamrahShahrPlus Mobile Banking App (CityDi)": (
                "Developed a Flutter mobile banking app with 1.7M+ users "
                "across Android, iOS, and web."
            ),
            "Vehicle Overload Detection System": (
                "Built the backend with Flask and MongoDB and developed "
                "a Windows desktop application with Flutter."
            ),
        }
```
