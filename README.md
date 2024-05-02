# miRNA-neural-network
A function to prepare the neural network sequence for the miRNA predictions. It uses the target prediction and the transcript and prepares the targets for the neural networks.a machine learning preparation for the microRNAs after the target predictions. It will extract the  microRNA binding sites and also the upstream and the dowstream to prepare for the motif machine learning.

```
preparemiRNAsML("/Users/gauravsablok/Desktop/release/Athaliana_167_TAIR10.transcript.fa", \
                                                "/Users/gauravsablok/Desktop/release/test.txt", \
                                                                 expectation_value="0.0", \
                                                                  upstream = 100, downstream=100)
````

Gaurav \
Academic Staff Member \
Bioinformatics \
Institute for Biochemistry and Biology \
University of Potsdam \
Potsdam,Germany 
