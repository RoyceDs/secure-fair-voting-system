# secure-fair-voting-system

## Instructions:

1. Fork the github repo into your personal Github account and take a clone into your local system.
    
    Guide to Forking Github Repo: https://docs.github.com/en/github-ae@latest/get-started/quickstart/fork-a-repo
    
    Guide for cloning Github Repo: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
    
2. Instantiate Virtual Studio code or any Development environment of your choice to complete the assessment in your local working directory.
3. Save the files and push it into forked Github github repo.
    
    Guide to pushing code into Github Repo: https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github
    
4. Record a screencast video recording demonstrating the solution in your system and upload the video into the forked github repo.
    
    Guide to record screen in
    
    a) MAC: https://support.apple.com/en-in/102618
    
    b) Windows: https://www.microsoft.com/en-us/windows/learning-center/how-to-record-screen-windows-11
    
    c) Ubuntu: https://askubuntu.com/questions/4428/how-can-i-record-my-screen
    
5. Share the repository link into the Google Form: [https://forms.gle/2HbLP8GNiYArZFsj8](https://forms.gle/ufqFg2Kgk5C54Amn7)


## Problem Statement:

Your task is to create a robust voting algorithm for a system where each voter is allocated 10 votes and can freely distribute them among 6 candidates. The challenge is to ensure fairness while mitigating strategic voting manipulation.

**Scenario**:

- Each voter can distribute their 10 votes across the 6 candidates however they want (e.g., 4 votes to Candidate A, 3 votes to Candidate B, 1 vote each to Candidates C, D, E, F).
- The system must detect and reduce the impact of strategic voting, where voters may intentionally skew results by allocating all their votes to a single candidate.
- The system should assume that strategic voting happens up to 45% of the time.

**Requirements**:

- The input will be provided in CSV format (each row representing a voter and their allocated votes).
- The system must output the most eligible candidate, considering fairness and minimizing the effect of strategic voting.
- You must create a program that processes the CSV, evaluates the votes, and outputs the result.
- Document and include your approach to detecting and mitigating strategic voting.

**Deliverables**:

- A backend program that processes voting data and produces results.
- An explanation in the README about how your algorithm handles strategic voting.
- Ensure your solution can handle edge cases and larger datasets.

**Push the source code along with a demo video of your solution into the forked github repo. Share the repo link in the google form: [https://forms.gle/2HbLP8GNiYArZFsj8](https://forms.gle/ufqFg2Kgk5C54Amn7)**

