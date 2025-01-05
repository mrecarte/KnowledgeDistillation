# Teacher-Student Sentiment Classification on IMDb

This project implements a teacher–student network for binary sentiment classification using the IMDb Movie Reviews dataset. A pretrained transformer serves as the teacher model, and a smaller student model is trained via knowledge distillation.

## Objective
Train a teacher–student model for binary sentiment classification on IMDb movie reviews.

## Workflow
1. **Dataset**: 
   - IMDb Movie Reviews dataset loaded via Hugging Face or CSV.
   - Data split into train and test sets.

2. **Teacher Model**: 
   - Pretrained transformer (e.g., BERT) fine-tuned on IMDb data.

3. **Student Model**: 
   - Smaller model trained using knowledge distillation (learning from ground truth labels and teacher logits).

4. **Evaluation**:
   - Both teacher and student evaluated on the test set.
   - Key metrics: Accuracy, F1 score, AUC, etc.
   - Comparison of teacher vs. student performance.

## Results
- Evaluation of teacher and student models highlights performance retention in the student.
