# Authentype

Authentype is a novel method for two-factor authentication. Using typing dynamics, the identity of a user can be verified. Even if a malicious agent were to gain access to a user's password, they still would not be able to mimick the user's distinctive typing style. How long do people press particular keys? How long do they take to move between keys? We use the Kolmogorov–Smirnov test to evaluate the statistical similarity betweem an authentication test round and a corpus of training data. We consider similarity of keystroke dynamics on two dimensions: digraph latency (time between keystrokes) and hold time (length of time a key is pressed down). Using a linear combination of statistically transformed Kolmogorov-Smirnov test results, we determine a threshold heuristic for verifying a user's authentication test against the biometric signature created from their training data.

![classification heatmap](/heatmap_classification.png?raw=true "Classification scores")
Classification scores for 5 trials of test data from each of 10 users. Each trial tested against that user's remaining trials or another user's set of trials using Authentype.
