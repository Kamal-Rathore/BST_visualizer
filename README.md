# My code file is in the master branch of my GitHub repository, and you can view it from [here](https://github.com/Kamal-Rathore/BST_visualizer/blob/master/bst.java) .
# BST_visualizer
# Binary Search Tree Visualizer

This is a Java-based project for visualizing a Binary Search Tree (BST) using Swing for graphical representation. The project includes functionality to add and delete nodes, as well as to display the inorder, preorder, and postorder traversals of the tree.

## Features

- Visual representation of the BST.
- Add nodes to the BST.
- Delete nodes from the BST.
- Display inorder, preorder, and postorder traversals.
- Display the height of the BST.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- An IDE or text editor of your choice.

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Kamal-Rathore/BST_visualizer.git
    cd BST_visualizer
    ```

2. Open the project in your preferred IDE.

3. Run the `bst.java` file to start the application.

## Usage

1. **Adding a Node**:
   - Enter the integer value in the text field.
   - Press the `Add` button or type 'a'/'A' and press Enter to add the node to the BST.

2. **Deleting a Node**:
   - Enter the integer value in the text field.
   - Press the `Delete` button or type 'd'/'D' to delete the node from the BST.

3. **Viewing Traversals and Height**:
   - The inorder, preorder, and postorder traversals are displayed in the info panel at the bottom.
   - The height of the BST is displayed on the top left.

## Example

The `main` method contains an example demonstrating the functionality:

```java
public static void main(String arg[]) {
    bst obj = new bst();

    obj.add(500);
    obj.add(250);
    obj.add(350);
    obj.add(200);
    obj.add(750);
    obj.add(1000);
    obj.add(700);
    obj.add(740);
}
