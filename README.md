# Github-Simulation-
Its a 4th semester project of data structures in which we are going to implement the knowledge of double pointers , link list , Polymorphism, graphs, tree and hashing

Instructions you must follow
1. Utilize Git for version control throughout the project. One team member is tasked with creating a
private repository on GitHub, to which all other team members will be added as collaborators.
2. Use 3 file structure and OOP concepts in your project.
3. Ensure that your program load all data from the CSV files provided for the project.
4. Create a brief screen recording demonstrating the functionality of your project.
5. Finalize your project submission by pushing all code and the report file to the GitHub repository
before the specified deadline. Additionally, submit a single Word document through Google
Classroom (GCR) containing a link to your GitHub repository.

Bonus work
● Implement the whole project in GUI using windows form.
● Use branching in GitHub.
● Well prepared readme file with proper pictures, videos, and project description.

Introduction
In this semester project, students will apply their knowledge of data structures by designing and
implementing a GitHub Simulation Console Application using C++. This project aims to simulate basic
functionalities of GitHub, such as repositories, commits, and user interactions, in a console application.
Through this project, students will gain hands-on experience with real-world applications of data structures
and develop their programming skills.

Objectives
● Understand and apply various data structures in a software project.
● Develop a console application in C++ that simulates key features of GitHub.
● Enhance problem-solving and programming skills in a real-world application context.



Project Description
The GitHub Simulation Console Application will allow users to create accounts, manage repositories,
make commits, and follow other users. The application will be command-line based, focusing on the
application of data structures such as linked lists, trees, graphs, and hash tables.
What is GitHub?

Key Features
1. User Accounts
Registration: Allow users to create a new account with a unique username and password.
Login/Logout: Enable users to login and logout from their account.
Profile View: Users can view their/others profile, which includes their username, followers, repositories
and files in specific repository if the repository is public.

2. Repositories
Creation: Users can create new repositories.
Deletion: Users have the option to delete their repositories.
Fork: Users can copy the public repository including files and commits from any other use.
Visibility: User have option to make their repositories private or public at the time of creation.
Commit: Implement commits, allowing users to add “commits” to their repositories.
View Stats: Users can view repository stats such as: Repo name, Repo files, Repo commits, Repo fork
count

2.1. Files in repositories
Add Files: Users can add/push files to a specific repository.
Delete Files: Users can delete files from a specific repository.


4. Social Features
Follow/Unfollow: Users can follow or unfollow other users.

Note: On all above mentioned features the information/record of a specific user will automatically be
saved in CSV files after updating.

Feature Details
1. User Accounts
Data Structure: Hash Table
Usage: Hash tables are utilized for efficient user management, including registration, login, and profile
viewing functionalities. Hash tables allow for quick access to user information based on unique keys (e.g.,
usernames).
Management:
Registration: When a new user registers, their information is stored in the hash table with the username as
the key.
Login/Logout: The application queries the hash table to verify login credentials. Logout functionality
updates the user’s status without deleting any data.
Profile View: User profiles are retrieved using the hash table, displaying information like username,
followers, repositories.

2. Repositories
Data Structures: Trees, Linked lists
Trees:
Usage: Trees represent the hierarchical structure of repositories, where each node in a tree represents a
repository of specific user.

National University


Management: Each repository is a node in a tree. Operations like creation and deletion modify the tree
structure accordingly. The search time for repositories will be O(log n).

Linked Lists:
Usage: Each node representing a repository is further attached with two linked lists.
Management: A linked list to store commits where each node represents the commit, and a linked list to
store files where each node represents a file. New commits are added to the list’s head, preserving
chronological order.

3. Social Features
Data Structure: Graphs
Usage: Graphs are employed to represent the network of users, where vertices represent users and edges
represent follow relationships.
Management: When a user follows another, an edge is created between their vertices. Unfollowing
removes the edge.
