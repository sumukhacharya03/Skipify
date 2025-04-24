# Skipify
Deep Learning Model that categorizes songs based on Dislike

### Brief About the Project
Ever felt like you just *know* you’re going to hate the next song on your playlist? Or wondered if a computer could detect your imminent eye-roll at that pimple tutorial video? Well, look no further! This project leverages a deep learning model to predict your next digital dislike before you even hit that button. By analyzing patterns in content features and user behavior, our “Deep Dislike Detector” aims to spare you the agony of bad recommendations—one predicted thumb-down at a time.

### Why I Chose to Build a Deep Learning Model on Dislikes
- **Because hating things is fun:** Let’s be honest, clicking “Dislike” is oddly satisfying. Why not make an AI that revels in the drama too?
- **Better User Experience:** Platforms thrive on likes, but dislikes tell you more. A model that preempts dislikes can improve recommendations and keep users happier (or at least less annoyed).
- **Untapped Potential:** While everyone’s busy predicting hits and viral content, we’re flipping the script to focus on the *not-so-popular*.

### Workflow of This Project
1. **Data Collection:** Collected more than 1000 audio files of various genres.
2. **Feature Extraction:** Extracted various features from the audio files using libraries like Librosa.
3. **Pipeline Setup:** Utilize Jupyter Notebooks (`Test Pipeline.ipynb`, `Train Pipeline.ipynb`) to orchestrate data preprocessing, model training, and evaluation.
4. **Model Architecture:** Implement a multi-layer feedforward network (or CNN/RNN where appropriate) with dropout and batch normalization.
5. **Training & Validation:** Split data into train/val/test sets, tune hyperparameters, and track metrics like accuracy, recall, and false-positive rate.
6. **Testing:** Tested the above model on a randomly unseen audio file, which gives it a "skip" or "not skip" label.

### Future Work
- **Incorporate Sequential Models:** Experiment with Transformer-based architectures to capture temporal patterns in user behavior.
- **Cross-Domain Learning:** Transfer learning from one content domain (e.g., music) to another (e.g., videos, articles).
- **Real-time Feedback Loop:** Use live user feedback to continuously fine-tune the model in production.
- **Personalization Layer:** Add user-specific embeddings for more tailored dislike predictions.
- **Memory Module:** Introduce a memory network to remember long-term user preferences (and aversions).
