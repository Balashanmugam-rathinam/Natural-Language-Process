📄This Python program demonstrates a basic Natural Language Processing (NLP) task using NLTK. It tokenizes a sample text into individual words and symbols using TreebankWordTokenizer, then calculates how frequently each token appears using FreqDist. Finally, it visualizes the token frequency using a simple bar chart created with Matplotlib.

🧠 Key Features:
Tokenizes a sentence into words and punctuation.

Counts the frequency of each token.

Prints the tokens and their frequencies.

Displays a bar chart showing the token frequency distribution.

💻 Technologies Used:
-Python
-NLTK (Natural Language Toolkit)
-Matplotlib

🧪 Sample Output:

Tokens: ['Natural', 'Language', 'Processing', '(', 'NLP', ')', 'with', 'Python', 'is', 'fun', 'and', 'educational', '.', 'Python', 'simplifies', 'NLP', 'tasks', '.']

Word Frequency Distribution:
Natural: 1
Language: 1
Processing: 1
(: 1
NLP: 2
): 1
with: 1
Python: 2
is: 1
fun: 1
and: 1
educational: 1
.: 2
simplifies: 1
tasks: 1

A bar chart will also appear showing the same data visually.

📌 How to Run the Program:
Install the required libraries:

pip install nltk matplotlib
(Optional) Download NLTK resources if running for the first time:
import nltk
nltk.download('punkt')

Run the Python file:
python your_script_name.py
