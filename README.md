# TED Talk Summarization

This code summarizes a given TED Talk transcript using a combination of NLP techniques and machine learning algorithms. It can summarize multiple transcripts by randomly selecting a number of transcripts specified by the user. The summarized transcript is obtained by finding the similarity between different sentences in the original transcript and ranking them based on their similarity scores. The top ranked sentences are then selected to form the summary.
Requirements

## The code requires the following packages:

    numpy
    pandas
    bs4
    nltk
    os
    re
    urllib.request
    heapq
    networkx
    sklearn
    matplotlib

## Dataset

The code uses a dataset of TED Talk transcripts, which is stored in a csv file named transcripts.csv. The csv file contains two columns: transcript and url. The transcript column contains the transcripts of the TED Talks, and the url column contains the URLs of the corresponding TED Talks.
GloVe Model

The code uses the GloVe model, which is a word embedding model, to represent words as vectors. The GloVe model used in this code is stored in a txt file named glove.6B.300d.txt.
Usage

## The code can be run by executing the following steps:

    Clone the repository to your local machine.
    Navigate to the cloned repository in your terminal/command prompt.
    Run the code using the following command:

python summarize.py

    The code will prompt you to enter the number of transcripts you would like to summarize.
    The code will then randomly select the specified number of transcripts from the transcripts.csv file and summarize each of them.

## Output

The code produces the summarized transcript for each of the selected transcripts. The summarized transcript is printed in the terminal/command prompt along with the original transcript.
## Conclusion

This code provides an efficient way to summarize TED Talk transcripts by using NLP techniques and machine learning algorithms. By using the GloVe model to represent words as vectors, the code is able to accurately determine the similarity between different sentences in the original transcript and produce a high-quality summary.
