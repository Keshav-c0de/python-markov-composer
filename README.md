A Python-based Markov Chain text generator that "learns" the style of a source text (like Harry Potter) and generates new, original sentences in that same style.

🚀 How it Works

This project uses Graph Theory to model language:
1. Vertices (Nodes): Represent unique words.
2. Edges (Links): Represent the transitions between words.
3. Weights: Represent how frequently one word follows another.

The program builds a "probability map" of the text and uses a weighted random selection to "walk" through the graph and compose new text.

📂 Project Structure

* graph.py: Contains the Vertex and Graph classes that handle the data structure logic.
* compose.py: The main script that cleans the text, builds the graph, and generates the composition.
* texts/: Folder containing the source .txt files (e.g., hp_sorcerer_stone.txt).
