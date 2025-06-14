# Cognates-in-Character-Level-Embeddings

Intentionally (Underfitted?) Model

At least, I think it's partially underfitted. Some aspect of the transformer has to be well fitted or else you wouldn't get consistent-looking cognates. But if it weren't underfitted in some manner, you wouldn't get the pleasant diversion from Shakespeare's English.

Interestingly, the English generated by this modification of the model provided in Karpathy's nanoGPT repository (https://github.com/karpathy/nanoGPT) strikes me as overwhelmingly Scottish, though someone who knows Scottish would be needed to provide further insight, I only know what it sounds like. To get different results, try adjusting the hyperparameters. 

To generate these for yourself, head over to Karpathy's nanoGPT at the link above. Download the repo, and put it somewhere convenient. Copy the two files in this repository drop them in. If you want to run the one I trained, just use the command python3 sample.py --out_dir=out-shakespeare-char --device=cpu
