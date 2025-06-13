# TEXT-SUMMARIZATION-TOOL

COMPANY: CODTECH IT SOLUTION

NAME: SIPRA SHARMA

INTERN ID :CT06DG741

DOMAIN: ARTIFICIAL INTELLIGENCE

DURATION : 6 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION OF TASK : Here we done python programming for summarzing the long paragraph using NPL. The given Python script performs automatic text summarization using the TextRank algorithm from the Sumy library. It takes a lengthy article about machine learning and reduces it to its most essential sentences. The script begins by importing necessary modules such as PlaintextParser, Tokenizer, and TextRankSummarizer. The input article is defined as a multiline string and is parsed using PlaintextParser, which breaks the text into tokens using the English language tokenizer. The TextRankSummarizer is then used to analyze the structure of the text and detThis Python script uses the **Sumy** library to summarize a lengthy article about machine learning. The process begins by importing the necessary modules: `PlaintextParser`, `Tokenizer`, and `TextRankSummarizer`. These tools work together to break down and analyze text for summarization using the TextRank algorithm. The input is a multi-sentence article describing machine learning and its various applications in real-world scenarios like natural language processing, image recognition, autonomous vehicles, and more.

First, the `PlaintextParser` is used to convert the article from a plain string into a format that the summarizer can process. It uses the `Tokenizer`, configured for English, to divide the article into sentences and words. Tokenization is a critical preprocessing step, as it helps the summarizer understand the structure and components of the text.

Next, the `TextRankSummarizer` is initialized. This summarizer is based on the TextRank algorithm, which is an unsupervised graph-based ranking model. The algorithm represents sentences as nodes in a graph, connects them with edges based on sentence similarity, and ranks the importance of each sentence using methods inspired by Google’s PageRank. The most relevant sentences, according to their rank, are selected to form a concise summary.

In the script, the summarizer is instructed to extract the top **three** most important sentences from the article. These sentences are then printed as the summarized output. This approach is useful for quickly condensing large amounts of information into shorter, more digestible forms while retaining key insights. Overall, the script demonstrates a simple yet powerful method of automatic text summarization using natural language processing techniques.
ermine the importance of each sentence by creating a graph of sentence similarities. From this graph, it selects the top-ranked sentences that best represent the overall content. In this case, the summary is limited to three sentences. Finally, the original article and the generated summary are printed to the console. This approach is useful for condensing large amounts of textual data while retaining key information and is particularly helpful in natural language processing tasks like document summarization, news filtering, or quick content review.








