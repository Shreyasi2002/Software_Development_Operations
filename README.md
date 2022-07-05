# Software Development and Operations

## ClubZen IITK (Group Project)

Developed a cross-platform Web Application to integrate all clubs and societies under MnC, SnT, etc., and College fests in a modular format. A separate feed was created for each club and community.

The main features of the app are -
- Upcoming events and workshop section.
- All club activities and achievements are posted publicly.
- Students' works posting and reviewing.
- Contact with Secys and Coordinators.
- Forums section for interacting with clubs.
- Access levels with restrictions based on the position of individuals.

<img src="https://github.com/Shreyasi2002/CS253_Project/blob/main/images/home_page.jpg">

More details about the application can be found at - https://github.com/Shreyasi2002/CS253_Project

## Library Management System

Implemented Library Management System in C++ language on command line interface using Object-oriented programming concepts.

List of functionalities:
1. Implement Login Logout
2. Professor, Student and Librarian are child classes of User class.<br/>
    – Professor Can see all the books. Can see list of books s/he has. Can check if book is available for issue or not. Can issue infinite number of books. Can issue a book for 60 days. Fine is 5 rupees/day after due date.<br/>
    – Student Can see all the books. Can see list of books s/he has. Can check if book is available for issue or not. Can issue at max 5 books. Can issue a book for 30 days. Fine is 2 rupees/day after due date.<br/>
    – Librarian Can add/update/delete user or book. Can list down all books/users. Can check which book is issued to which user. Can check list of books issue to user.

```
     ____________________________________________________
    |____________________________________________________|
    | __     __   ____   ___ ||  ____    ____     _  __  |
    ||  |__ |--|_| || |_|   |||_|**|*|__|+|+||___| ||  | |
    ||==|^^||--| |=||=| |=*=||| |~~|~|  |=|=|| | |~||==| |
    ||  |##||  | | || | |JRO|||-|  | |==|+|+||-|-|~||__| |
    ||__|__||__|_|_||_|_|___|||_|__|_|__|_|_||_|_|_||__|_|
    ||_______________________||__________________________|
    | _____________________  ||      __   __  _  __    _ |
    ||=|=|=|=|=|=|=|=|=|=|=| __..\/ |  |_|  ||#||==|  / /|
    || | | | | | | | | | | |/\ \  \|++|=|  || ||==| / / |
    ||_|_|_|_|_|_|_|_|_|_|_/_/\_.___\__|_|__||_||__|/_/__|
    |____________________ /\~()/()~//\ __________________|
    | __   __    _  _     \_  (_ .  _/ _    ___     _____|
    ||~~|_|..|__| || |_ _   \ //\\ /  |=|__|~|~|___| | | |
    ||--|+|^^|==|1||2| | |__/\ __ /\__| |==|x|x|+|+|=|=|=|
    ||__|_|__|__|_||_|_| /  \ \  / /  \_|__|_|_|_|_|_|_|_|
    |_________________ _/    \/\/\/    \_ _______________|
    | _____   _   __  |/      \../      \|  __   __   ___|
    ||_____|_| |_|##|_||   |   \/ __|   ||_|==|_|++|_|-|||
    ||______||=|#|--| |\   \   o    /   /| |  |~|  | | |||
    ||______||_|_|__|_|_\   \  o   /   /_|_|__|_|__|_|_|||
    |_________ __________\___\____/___/___________ ______|
    |__    _  /    ________     ______           /| _ _ _|
    |\ \  |=|/   //    /| //   /  /  / |        / ||%|%|%|
    | \/\ |*/  .//____//.//   /__/__/ (_)      /  ||=|=|=|
  __|  \/\|/   /(____|/ //                    /  /||~|~|~|__
    |___\_/   /________//   ________         /  / ||_|_|_|
    |___ /   (|________/   |\_______\       /  /| |______|
        /                  \|________)     /  / | |

-----------------------WELCOME TO IIT KANPUR LIBRARY-----------------------
Choose your role :
1.Professor (Press 1 to select this role)
2.Student (Press 2 to select this role)
3.Librarian (Press 3 to select to role)
Press any other key and Enter to exit the application...
```

The implementation can be found at - https://github.com/Shreyasi2002/Library_Management_System

## Spam Classifier

Built a classifier to classify emails as spam or non-spam. We used the Kaggle dataset <a href="https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset">Spam or Not Spam Dataset</a> for this task.

Steps performed :

- Used the **Bag-of-Words** representation to process the text.
- Visualized the frequency of word-occurence in all the emails.
<img src="">
- Used **SVM** and **K-Nearest Neighbour** to build the classifier.

```
#### KNN Classifier with n_neighbors = 3 ####

Train Accuracy : 0.9254166666666667
Test Accuracy : 0.775
Train AUC Score : 0.9350768160648399
Test AUC Score : 0.8069168734491315

#### KNN Classifier with n_neighbors = 4 ####

Train Accuracy : 0.92375
Test Accuracy : 0.8083333333333333
Train AUC Score : 0.9158425573096233
Test AUC Score : 0.8080800248138958

#### KNN Classifier with n_neighbors = 10 ####

Train Accuracy : 0.9658333333333333
Test Accuracy : 0.9416666666666667
Train AUC Score : 0.9136877759632251
Test AUC Score : 0.854528535980149
```
