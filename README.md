🌸 Iris Flower Classification — Decision Tree (Python Project)
This project uses a Decision Tree classifier to categorize Iris flowers into three species — Setosa, Versicolor, and Virginica — based on their petal and sepal dimensions. It is a simple machine learning classification task ideal for beginners.

📂 Project Structure
nginx
Copy
Edit
Iris Flower Decision Tree/
├── Decision_Tree.py         # Main script to train and test the model
├── iris.csv                 # Dataset containing flower features and species
├── iris_tree.png            # Visualization of the trained decision tree
├── iris_tree.pdf            # PDF version of the tree visualization
├── get-pip.py               # Utility script to install pip (optional)
🚀 How It Works
Load the Iris dataset (iris.csv)

Train a Decision Tree Classifier using scikit-learn

Visualize the decision tree using graphviz

Predict and evaluate model performance

📦 Requirements
Install dependencies (if not already installed):

bash
Copy
Edit
pip install pandas scikit-learn matplotlib graphviz
▶️ Usage
bash
Copy
Edit
python Decision_Tree.py
Make sure Graphviz is installed and added to your system path for tree visualization.

🧪 Sample Output
Console will print model accuracy.

Tree diagram saved as iris_tree.png and iris_tree.pdf.

📈 Example Visualization

📊 Dataset
The dataset (iris.csv) contains 150 samples with the following columns:

sepal_length

sepal_width

petal_length

petal_width

species (label)
