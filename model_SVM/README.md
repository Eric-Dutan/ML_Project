# SVM_MODEL
This model uses a Support Vector Machine (SVM), which is a supervised learning technique. For each audio file, we extract Mel-Frequency Cepstral Coefficients (MFCCs), which capture important speech features such as pitch, tone, and pronunciation.

From the MFCCs, we compute summary features like the mean and standard deviation to form a fixed-length feature vector. Each vector is then assigned a label corresponding to the spoken command. The dataset is split into 80% training and 20% testing, where the SVM learns to separate classes by finding boundaries with maximum margin.

During the demo, a visualization of the MFCCs over time is shown. However, when we convert them into summary statistics, we lose the temporal information in the signal. Because of this, the SVM can only classify based on static features. In contrast, a CNN can learn directly from spectrogram images and preserve time-frequency structure, which is why it often performs better. This limitation can lead to confusion between similar words like “no” and “go.”
