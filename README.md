# French-to-English-using-Transformers

The model is implemented using standard Transformer
architecture consisting of encoder-decoder blocks. The encoding
takes the input English sentence and is converted into a
compressed latent vector. The latent vector is a summary of the
relationship between the English keywords. The decoder then
takes in the latent vector and outputs French transactions. As
the transformer lacks recurrence, the positional encodings pass
the positional information. The system is tested on a bilingual
dataset and is evaluated using bilingual Evaluation Understudy
BLEU score and compared to a baseline approach to showcase
computation efficiency and improved performance. The results
obtained by the transformer network indicate that transformers
are better at handling sequence-to-sequence tasks than
traditional RNNs and LSTMs. 

## Architecture of the transformer
![image](https://github.com/user-attachments/assets/b23fae73-330d-45de-a283-d9aa6f737d39)

### Plots
### Loss and Accuracy:
![image](https://github.com/user-attachments/assets/a5af0443-0a7b-48c3-bccf-5f8a19129668)

## sample test cases:
![image](https://github.com/user-attachments/assets/c2e2d6db-6ef2-4b15-b8bf-836a27524d8e)
