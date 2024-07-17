# Binary Search Tree (BST) Project

This project implements a Binary Search Tree (BST) in C++. It includes functionality for inserting nodes, searching for a node, deleting a node, and printing the tree structure in a readable format.

## Table of Contents
- [Binary Search Tree (BST) Project](#binary-search-tree-bst-project)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Input Example](#input-example)
    - [Output Example](#output-example)
  - [Functions](#functions)
  - [Contributing](#contributing)
  - [License](#license)

## Features
- Insert nodes into the BST.
- Search for nodes in the BST.
- Delete nodes from the BST.
- Print the tree structure in a readable format.

## Requirements
- C++11 or later
- A C++ compiler (e.g., g++)

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/projectBST1.git
    ```
2. Navigate to the project directory:
    ```sh
    cd projectBSTcode
    ```
3. Compile the program:
    ```sh
    g++ -o bst_program projectBSTcode.cpp
    ```

## Usage
1. Create an `input.txt` file in the project directory with the following format:
    ```
    <number of nodes>
    <value1>
    <value2>
    ...
    <valueN>
    ```
   Example:
    ```
    5
    10
    5
    20
    15
    25
    ```

2. Run the program:
    ```sh
    ./bst_program
    ```

3. The program will read from `input.txt` and output the results to `output.txt`.

### Input Example
`input.txt`:
5
10
5
20
15
25

### Output Example
`output.txt`:
Tree structure after insertion:
10
5 20
15 25

Enter key to search:
Key 15 found in the tree.
Tree structure after search:
10
5 20
15 25

Enter key to delete:
Tree structure after deletion:
10
5 20
25


## Functions
- `Node* newNode(int key)`: Creates a new node with the given key.
- `Node* insert(Node* root, int val)`: Inserts a node with the given value into the BST.
- `Node* search(Node* root, int key)`: Searches for a node with the given key in the BST.
- `Node* deleteNode(Node* root, int key)`: Deletes a node with the given key from the BST.
- `void printLevelOrder(Node* root)`: Prints the tree structure in level-order (breadth-first) traversal.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

License File (LICENSE)
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

