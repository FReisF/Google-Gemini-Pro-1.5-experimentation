The main point in this repository are the two notebooks and the large csv file saved.

csv file: df_bulas_split.csv
first notebook: PJT Chatbot - Bulas - first step with prep and tests.ipynb
second notebook: PJT_Chatbot_Bulas_working_with_csv_only.ipynb



The fist nobook is a preparation of several pdf files containin drug leaflets in portuguese. They are merged, the text is split and embeddings are created for them.
The final output is saved as a csv as this preparation step is quite long and is easier to go from the ready data afterwards
On this notebook there are also some attempts to build a user request based chatbot to retrieve information contained in the leaflets based on user input.
It is important to note that the outputs for this part are not coherent at all.


The second notebook takes the data already directly from the csv saved file and reads as pd. It prepares the embeddings column to contain arrays again.
It applies a method also to find information on the leaflets based on user input. Although far from precise and accurate the results are way better than the ones attempted on the first notebook,
