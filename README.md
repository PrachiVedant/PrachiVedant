```python
class AboutMe:
    def __init__(self):
        self.current_mission = "Democratizing AI through open-source"
        self.tech_stack = {
            "𝗟𝗮𝗻𝗴𝘂𝗮𝗴𝗲𝘀": ["Python", "Rust", "SQL"],
            "𝗠𝗟 𝗙𝗿𝗮𝗺𝗲𝘄𝗼𝗿𝗸𝘀": ["PyTorch (Lightning)", "TensorFlow", "HuggingFace"],
            "𝗠𝗟𝗢𝗽𝘀": ["Docker", "Kubeflow", "MLflow", "TFX"],
            "𝗖𝗹𝗼𝘂𝗱": ["AWS SageMaker", "GCP Vertex AI", "ONNX Runtime"]
        }
        self.interests = [
            "Multi-modal foundation models", 
            "Edge AI deployment",
            "Neuro-symbolic systems"
        ]
        
    def __str__(self):
        return f"{self.current_mission} with {len(self.tech_stack)} core competencies"
```
