# Squeezing More Info Out of Fraud Data with Statisticis

This repository gives the Python behind a November 2025 LinkedIn post. 

## The LinkedIn Post

TBD 

## How to Run the Notebook on Google Colab

To run the Jupyter Notebook interactively on Google Colab while accessing the private package, you need to provide a GitHub Personal Access Token (PAT) with read access to a private repo.

### Steps:

1. **Open the Notebook in Colab**

   Click the Colab badge or open [squeezing-more-info-out-of-fraud-data-w-statistics.ipynb](https://colab.research.google.com/github/dglassbrenner1/squeezing-more-info-out-of-fraud-data-w-statistics/blob/main/squeezing-more-info-out-of-fraud-data-w-statistics.ipynb) to open the notebook in Google Colab.

2. **Create a GitHub Personal Access Token (PAT)**

   - Go to your GitHub [Personal Access Tokens](https://github.com/settings/tokens) settings.
   - Generate a **Fine-Grained Personal Access Token** with the following:
     - Repository access: select your private repo `my_private_package_repo`.
     - Permissions:
       - Contents: Read-only
       - Metadata: Read-only
     - Set an expiration date (optional but recommended).
   - Copy the token immediately; you won't see it again.

3. **Add the Token to Colab Secrets**

   - In Colab, open the left sidebar, click **Secrets** (key icon).
   - Click **Add a new secret**.
   - Set the name as `GITHUB_PAT`.
   - Paste your GitHub token as the value.
   - Save and enable access for the notebook.

4. **Run the Notebook**

   You should now be able to run the notebook on Colab.


## Colab Badge

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dglassbrenner1/squeezing-more-info-out-of-fraud-data-w-statistics/blob/main/squeezing-more-info-out-of-fraud-data-w-statistics.ipynb)

---

Thank you and enjoy!

If you have any issues or questions, please open an issue in this repository.
