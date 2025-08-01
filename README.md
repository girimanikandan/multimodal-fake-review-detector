# Multimodal Fake AI Review Detector for E-commerce
A novel AI system to detect fake reviews using text, images, behavioral patterns, and temporal analysis.

## Core Innovation
First system to integrate:  
✅ **Text**: BERT-based LLM detection.  
✅ **Images**: GAN artifact detection.  
✅ **Behavior**: Flags rapid posting bursts.  
✅ **Temporal**: Detects coordinated review timing.  

**Why It’s New**:  
- Unlike [Hou et al. 2025](https://www.sciencedirect.com/science/article/abs/pii/S1567422325000109), which uses text and images, this combines four modalities with explainable outputs.  
- Tailored for e-commerce, unlike news-focused systems.

## Evidence of Novelty
| Aspect | Existing Solutions | Our Approach |
|--------|--------------------|--------------|
| Modalities | 1-2 (text/image) | 4+ (text, image, behavior, time) |
| Domain | News/Social Media | E-commerce |
| Explainability | Black-box | Human-readable reasons |

**Verification**: Google Scholar and ResearchGate (last checked: 01-Aug-2025) found no matches.

## Technical Preview
```python
class FakeReviewDetector:
    def analyze(self, review):
        text_score = self.bert_text_analysis(review.text)
        image_score = self.gan_image_check(review.image)
        behavior_score = self.user_activity_score(review.author)
        time_score = self.temporal_anomaly(review.timestamp)
        return f"Risk: {self.fuse_scores(text_score, image_score, behavior_score, time_score)}"
## Intellectual Property
(c) 2025 [GIRIDHARAN M, DEENA.T.A ]. All rights reserved.  
Prior art established via this repo.

