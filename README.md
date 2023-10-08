# miRNA_neural_network
A function to prepare the neural network sequence for the miRNA predictions. It uses the target prediction and the transcript and prepares the targets for the neural networks.a machine learning preparation for the microRNAs after the target predictions. It will extract the  microRNA binding sites and also the upstream and the dowstream to prepare for the motif machine learning.

```
preparemiRNAsML("/Users/gauravsablok/Desktop/release/Athaliana_167_TAIR10.transcript.fa", \
                                                "/Users/gauravsablok/Desktop/release/test.txt", \
                                                                 expectation_value="0.0", \
                                                                  upstream = 100, downstream=100)
````

Gaurav Sablok \
ORCID: https://orcid.org/0000-0002-4157-9405 \
WOS: https://www.webofscience.com/wos/author/record/C-5940-2014 \
RubyGems Published: https://rubygems.org/profiles/sablokgaurav \
Python Packages Published : https://pypi.org/user/sablokgaurav/
