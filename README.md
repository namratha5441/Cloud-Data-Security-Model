# Optimized Key Generation and Deep Learning Model for Cloud Security
This research aims to design and develop a secure mechanism for cloud data protection and attack detection. The project consists of two main modules: Data Protection Scheme and User Attack Detection Module.<br/>
![image](https://github.com/user-attachments/assets/7bdc67cf-cfb5-439d-a93c-f612b2848a91)

# Modules:
**1. Data Protection Scheme**<br/>
Data is split into chunks and encrypted before being uploaded to the cloud.
Encryption is based on a modified Huff scheme with an optimal key generation approach inspired by coati and coyote characteristics.
Privacy Preservation is ensured through data sanitization.<br/>
**2. User Attack Detection Module**<br/>
Deep Learning Model for attack detection utilizing the BoT-IoT dataset.
Features a Bidirectional LSTM (BiLSTM) with attention layers encapsulated in encoder-decoder modules.
The model focuses on identifying potential attackers through attention mechanisms and optimally tuned parameters.
# Key Components:
**Confidentiality:**<br/>
Asymmetric encryption (1:1) and ABE model (1
).
Includes byte substitution, row shifting, column mixing, and round key generation.
**Authentication:**<br/>
Modified hashing for generating 512-bit and 1024-bit keys.
Incorporates byte substitution, row mixing, and column shifting.
**Deep Learning for Attack Detection:**<br/>
BiLSTM processes input sequences in both forward and backward directions.
An attention mechanism highlights crucial input sequence elements for better attack detection.
A context vector is used to improve attack detection accuracy.
# Implementation:<br/>
The project is implemented in Python and evaluated based on data privacy, detection accuracy, precision, and recall.
A comparative analysis with existing methods will be provided.
