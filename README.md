# Zip Tree and Skip List

The **Zip Tree and Skip List** project provides implementations of two advanced data structures: the **Zip Tree** and the **Skip List**. These data structures offer efficient solutions for maintaining ordered sets with operations such as insertion, deletion, and search. Both data structures provide probabilistic balancing, ensuring good performance in average cases.

## Features
- **Zip Tree Implementation**: A fast and simple alternative to AVL and Red-Black Trees with easy-to-understand balancing logic.
- **Skip List Implementation**: A probabilistic data structure that provides logarithmic search, insertion, and deletion operations.
- **Python-Based**: Implemented in Python with clear and well-documented code, making it easy to understand and modify.
- **Efficient Performance**: Both data structures offer expected O(log n) performance for insertion, deletion, and search operations.

## Technologies Used
- **Python**: The project is entirely written in Python for simplicity and portability.

## Project Structure

```bash
├── metadata.yml              # Metadata for the project
├── requirements.py           # Python requirements (if any)
├── skip_list.py              # Skip List implementation
└── zip_tree.py               # Zip Tree implementation
```
## Installation
Clone the repository:
git clone https://github.com/SushmithaJagannath21/Zip_Tree_and_Skip_List.git

Navigate to the project directory:
cd Zip_Tree_and_Skip_List

Install any required dependencies:
pip install -r requirements.py

## Usage
Zip Tree: You can use the zip_tree.py to create and manipulate a Zip Tree. Here's an example:

from zip_tree import ZipTree

tree = ZipTree()
tree.insert(10)
tree.insert(20)
tree.delete(10)
print(tree.search(20))  # Output: True
Skip List: The skip_list.py contains the Skip List implementation. Example usage:

from skip_list import SkipList

slist = SkipList()
slist.insert(15)
slist.insert(30)
slist.delete(15)
print(slist.search(30))  # Output: True
