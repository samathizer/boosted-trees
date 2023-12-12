# Structuring Boosted Trees

This notebook shows two ways to bring structure into a boosted trees model:

1. Interaction constraints
2. Monotonic constraints

## Data

We use a motor third-part liability (MTPL) pricing dataset that describes 1 Mio insurance policies and their corresponding claim counts, see Mayer, M., Meier, D. and Wuthrich, M.V. (2023) SHAP for Actuaries: Explain any Model. http://dx.doi.org/10.2139/ssrn.4389797.

The dataset was synthetically generated, see above link for the underlying true model. It can also be downloaded from https://www.openml.org/search?type=data&status=active&id=45106.
