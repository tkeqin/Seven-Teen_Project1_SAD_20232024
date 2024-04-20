# 4.0 Proposed Solution

## 4.1 Solution

### 1. Implement additional search filters
As stated in the problem statement, the search engine of our electronic library system lacks in certain ways that would inconvenience the students and users. Therefore, we proposed to add additional search keywords that could help identify the book in search and at the same time filter out irrelevant searches. For example, we proposed to add the date of its publication as a filter key so that only books that are published in that year will be shown as the result. Secondly, we could also add a language filter for students searching for materials in certain languages such as Malay, English et cetera. With the language filter, users will be able to exclude books and materials in other languages that wouldn’t be helpful to the user.

### 2. Implement automated check-in and check-out system
As data errors become more frequent in the system, we proposed to implement a kind of automated check-in and check-out system that could shorten the process of loaning and returning books whilst being able to reduce manual errors and streamline processes. By implementing an automated system, the librarians on duty would be free to attend to other more important tasks in the library and not only be confined to the repetitive tasks of processing loan and return requests from students behind desks. More importantly, the automated check-in and check-out system would be able to receive and store data more accurately in its system by automatically inputting data. With a system like this, data errors aren’t prone to happen as often as it is with manual inputting and storing. The probability of obtaining wrongful data about overdue books and charged fines will also be lower when a fully automated processing machine is in run.

### 3. Implement an online reservation system
As mentioned, students are often inconvenienced when it comes to book reservation and the checking of book availability in the library. Thus, we proposed to implement an online reservation system. An online reservation system which can allow students to check on desired books availability could largely help students and users in their search for it. By doing so, users could often save much precious time without needing to physically check in the library to know if a certain book is available. They would be able to do it remotely. If it so happens that the book desired appears to be available in the system, the user could immediately reserve the book online and be given a certain amount of time to pick it up from the library.

### 4. Develop automatic process for the addition, update and removal of records
Not only manual loaning and returning systems are prone to errors in databases, the addition, update and removal of new users and new book inventories also face problems in the inaccuracy of data. By developing an automatic process for this, data of new students could be added into the library database automatically through the linking of student data from the university database. The same goes for the process of removing students. When a student is no longer studying in the university, data of that particular student will be removed from the university database and in turn removed from the library database as well. For the updating of book inventories status such as newly added into the collection, damaged, lost, replaced et cetera, could be updated in the database through an automated system that simplified the input process by library staff and linked to the library records. 

### 5. Introduce data backup as a security measure
Since the loss of data in databases is often irreversible and consequential, it would be a good idea to implement data backup features in the system. With data backups, library records for users and book inventories could be safeguarded against the accidental deletion and other causes of data loss. Even if a staff accidentally deleted or wrongfully altered the records, we could always trace back in backups to recover the lost or altered data. This could help in various occasions when manual mistakes or deliberate sabotage are done to the database. 



## 4.2 Feasibility Study

### 1. Operational Feasibility
Since librarians are hired to carry out most of the processing in the library, thus we could ensure human resources are always available to operate the new digital library management system that we are proposing here. Although it might prove to be time consuming to persuade and train librarians in using the new library system, that is a problem that can be overcome. Thus, we can conclude that the new proposed library system is operationally feasible.

### 2. Technical Feasibility
From the aspect of technicality, we currently do not have enough technical resources for us to upgrade the library system. To shape the new system by adding the features mentioned above, we will need to develop an automation system within the library management system for students to check-in and check-out books. Then, we would also need to add filters and keywords into the search engine in the library website. Other than that, a brand new real-time update system and online book reservation system would also need to be developed and implemented into the library website as an additional feature. Data backup would also be required to be introduced into the new system. Thus, by the amount of new developments and implementations we wished to do to the current system, we would need to upgrade our current technology level as well since the current technology level is insufficient. Therefore, we can conclude that it is technically feasible as upgrades can be done. 

### 3. Economic Feasibility (CBA)
The following is a cost-benefit analysis done to assess the economic feasibility of developing a new system for a library management system.

| Assumptions                       |     | 
|-----------------------------------|-----|
| Discount rate                     | 10% |
| Sensitivity factor (cost)         | 1.1 |
| Sensitivity factor (benefit)      | 0.9 |
| Annual change in production costs | 7%  |
| Annual change in benefits         | 5%  |

| Estimated Cost                                          |           | 
|---------------------------------------------------------|-----------|
| Software development                                    | RM 8 000  | 
| Hardware (servers, networking equipment, cloud service) | RM 20 000 | 
| Training                                                | RM 8 000  | 
| Maintenance                                             | RM 3 000  |
| Networking personnel                                    | RM 15 000 |

| Estimated Benefits                                            |           | 
|---------------------------------------------------------------|-----------|
| Reduced administrative costs (manual labour and paperwork)    | RM 20 000 |
| Reduced staffing costs                                        | RM 15 000 |
| Revenue opportunities (advertising, partnership, sponsorship) | RM 30 000 |
| Maintenance                                                   | RM 3 000  |
| Networking personnel                                          | RM 15 000 |

| Costs                   | Year 0 | Year 1 |   Year 2 |   Year 3 |
|-------------------------|-------:|-------:|---------:|---------:|
| Development Costs       |        |        |          |          |
| Software development    |   8800 |        |          |          |
| Hardware                |  22000 |        |          |          |
| Training                |   8800 |        |          |          |
|                   Total |  39600 |        |          |          |
|                         |        |        |          |          |
| Production Costs        |        |        |          |          |
| Maintenance             |        |   3300 |     3531 |  3778.17 |
| Networking personnel    |        |  16500 |    17655 | 18890.85 |
|                         |        |        |          |          |
| Annual Production Costs |        |  19800 |    21186 | 22669.02 |
| (Present value)         |        |  18000 | 17509.09 | 17031.57 |
|                         |        |        |          |          |
| Accumulated Costs       |        |  57600 | 75109.09 | 92140.66 |

| Benefits                              | Year 0 |    Year 1 |   Year 2 |   Year 3 |
|---------------------------------------|-------:|----------:|---------:|---------:|
| Reduced administrative costs          |        |     18000 |    18900 |    19845 |
| Reduced staffing costs                |        |     13500 |    14175 | 14883.75 |
| Revenue opportunities                 |        |     27000 |    28350 |  29767.5 |
|                                       |        |           |          |          |
| Annual Benefits                       |        |     58500 |    61425 | 64496.25 |
| (Present value)                       |        |  53181.82 | 50764.46 | 48456.99 |
|                                       |        |           |          |          |
| Accumulated Benefits  (Present value) |        |  53181.82 | 103946.3 | 152403.3 |
|                                       |        |           |          |          |
| Gain or Loss                          |        | (4418.18) | 28837.19 | 60262.61 |
|                                       |        |           |          |          |
| Probability Index                     |        |  1.521783 |          |          |

Based on the calculations, it is shown that the probability index is 1.52, which is higher than 1, indicating that the new system will be a good investment and economically feasible.
