# Plant Classification and Disease Recognition

## objectives:
#### (stage 1) -> plant type classification 
- train a model to classify plant type (in 9 classes).
- use classical computer vision or deep learning techniques.
- validate accuracy .

#### (stage 2) -> Disease Recognition
- train one/few shot learning model (Siamese network) to detect diseases.
- Handle cases involving unseen plant categories.

## Requirements  

#### Stage 1: plant type classification
- Must use a classification model (SVM, logistic regression, or deep learning).
- For classical computer vision, use feature extraction methods like SIFT or BoW before classification.
#### Stage 2: Disease Recognition
- Train a one/few-shot learning model (e.g., Siamese network).

## Deliverables
- Code for both classification and recognition tasks.
- Training outputs/logs (notebooks with cells saved or IDE screenshots).
    - will use ide (vs code)
- Test scripts for accuracy evaluation:
    - For Stage 1: Classify plant types.
    - For Stage 2: Handle cases with unseen images and new plant categories. (reference image(Anchor))
- report detailing:
    - Data preparation, techniques, training/testing times.
    - Accuracy metrics and visualizations.
    - Description of one/few-shot model performance.

## Tools

- python
- visual studio code

### Environment
- install anaconda
- run anaconda prompt
- run this commands
    - conda create --name environment-name
    - conda activate environment-name
    - cd anaconda, cd envs, cd environment-name
    - conda install ipykernel
    - conda install opencv
    - conda install numpy
    - conda install matplotlib
    - conda install scikit-learn
