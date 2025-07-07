Referring to https://github.com/karpathy/build-nanogpt

Acknowledgement of Andrej karpathy and other online blogs

Since we are unable to download the dataset of fineWeb due to Colab space constraint, we switch to other datasets

wikitext is not large but contains short sentences that are often not related to one another.

tinystories contain consistent short stories,seem  suitable for a mini training

Code snippet shows steady decrease of loss function. The text output shows limitations due to the small size of dataset, uncleaned line changing token and too large vocab size. However, this is an educational attempt of building gpt functionalities at nano scale.
