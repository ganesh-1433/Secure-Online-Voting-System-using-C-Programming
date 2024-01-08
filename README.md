# Secure-Online-Voting-System-using-C-Programming
Abstract:
In the contemporary era, technological advancements have permeated every aspect of our lives, including the way we conduct elections. The proposed project is a Secure Online Voting System implemented in C programming. The system ensures the integrity and security of the election process by incorporating features such as user authentication, candidate registration, and secure voting mechanisms. The project encompasses both administrative and student panels, offering distinct functionalities to each.

Introduction:
Elections are a cornerstone of democratic societies, and as we transition into the digital age, the need for secure and efficient online voting systems becomes increasingly evident. The proposed system aims to provide a robust platform for conducting elections, maintaining the confidentiality of votes, and ensuring a fair and transparent electoral process.

System Architecture:
The system consists of two main components: the administrative panel and the student panel.

1. Administrative Panel:
   - Authentication: The system ensures secure access to administrative functionalities through username and password authentication.
   - New Election Initiation: The administrator can initiate a new election by providing essential details such as the election year, branch code, total number of voters, and the number of candidates.
   - Candidate Registration: The administrator can register candidates for the election, assigning a unique candidate ID and collecting their names.
   - Vote Management: The administrator has the authority to delete illegal votes based on user ID, ensuring the integrity of the election results.
   - User Ban: The administrator can ban specific user IDs, preventing them from participating in the election.
   - Result Declaration: The system can compute and display election results, including the winning candidate and the overall voting percentage.

2. Student Panel:
   - User Authentication: Students must provide a valid user ID to participate in the election.
   - Validation and Authorization: The system validates user IDs based on the election year, branch code, and roll number. It also checks whether the user has already voted or is banned.
   - Voting: Students can cast their votes securely by choosing a candidate from the list of registered candidates.
   - Confidentiality: The system ensures the confidentiality of votes by associating each vote with a unique user ID without revealing the voter's identity.
   - Exit Option: Students can exit the voting process by entering '0.'

Code Description:
The C programming code provided establishes the foundation for the Secure Online Voting System. It includes essential functionalities such as user authentication, candidate registration, voting, and result computation. The code employs structures to store information about candidates and the current valid user ID. It also utilizes file handling to store and retrieve election-related data.

Security Measures:

1. User Authentication:
   - The administrative panel requires a username and password for access, enhancing security.
   - Student panel authentication ensures the validity of user IDs, preventing unauthorized access.

2. Confidentiality:
   - The system ensures the confidentiality of votes by associating votes with unique user IDs.
   - Banned user IDs and illegal votes can be managed by the administrator, maintaining the integrity of the election.

3. Data Integrity:
   - The system tracks votes in candidate-specific files, allowing for the secure and accurate management of votes.
   - Illegal votes can be deleted without compromising the overall integrity of the election process.

Conclusion:
The proposed Secure Online Voting System in C programming provides a robust framework for conducting elections securely and efficiently. With features such as user authentication, candidate registration, and secure voting mechanisms, the system addresses key concerns associated with online elections. As technology continues to play a pivotal role in shaping democratic processes, this project serves as a foundational step toward building trustworthy and secure online voting systems.
