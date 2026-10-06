# Customer feedback NLP pipeline

Colab notebook for the five-task NLP assignment on Trustpilot UK reviews.

## Files

- `Customer_Feedback_NLP_Pipeline.ipynb` - the full notebook (Tasks 1 to 5).
- `trustpilot_reviews.csv` - the 20,400-review subset used in the notebook (3,400 reviews from each of six sectors, fixed seed 42).

## Original dataset

Broughton, J. (2025) _Trustpilot Reviews 123k_ [Dataset]. Hugging Face.
https://huggingface.co/datasets/Kerassy/trustpilot-reviews-123k

The subset is drawn from the six sectors Animals & Pets, Electronics & Technology, Health & Medical, Money & Insurance, Restaurants & Bars and Travel & Vacation. If `trustpilot_reviews.csv` is missing, the notebook rebuilds it from the original dataset and checks it matches the reported sample.
