```python
from dataclasses import dataclass
from typing import List


@dataclass
class MLEngineer:
    name: str
    role: str
    focus_areas: List[str]
    engineering_stack: List[str]
    current_work: str
    research_interests: List[str]
    philosophy: str

    def introduction(self):
        print(
            "Hello 👋  I'm Anjali.\n"
            "I build machine learning systems that go beyond notebooks —\n"
            "end-to-end pipelines, deployed models, and measurable outcomes.\n"
            "Ask me about my projects below. ↓"
        )


me = MLEngineer(
    name="Anjali Yadav",
    role="Machine Learning Engineer",  
    focus_areas=[
        "End-to-End ML Pipelines",
        "Deep Learning & Model Optimization",
        "MLOps & Production Deployment",
        "Statistical Modeling",
    ],
    engineering_stack=[
        "Python · PyTorch · TensorFlow",
        "scikit-learn · MLflow · FastAPI",
        "Docker · AWS · GCP",
        "SQL · MongoDB",
    ],
    current_work="Designing robust ML systems with measurable real-world impact.",
    research_interests=[
        "Transformers & Attention Mechanisms",
        "Representation Learning",
        "Generative & Agentic AI",
        "Efficient Inference & Model Compression",
    ],
    philosophy=(
        "Strong baselines beat clever tricks. "
        "If it doesn't evaluate well, it doesn't ship."
    ),
)

me.introduction()
```
