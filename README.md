1. Create a New Branch


git branch feature-update

<img width="838" height="247" alt="image" src="https://github.com/user-attachments/assets/637a8554-bd89-4b07-b0c6-0ad7ee297bfa" />

2. Switch to the New Branch

git checkout feature-update

<img width="940" height="155" alt="image" src="https://github.com/user-attachments/assets/7d4467d0-c193-47a5-a641-8053a137262c" />

3. Modify `app.py` with New Feature

<img width="473" height="166" alt="image" src="https://github.com/user-attachments/assets/d8de6d42-60cf-4dfd-aaca-b84bcb648106" />

4. Stage and Commit Changes

git add .
git commit -m "Devops added"

<img width="872" height="300" alt="image" src="https://github.com/user-attachments/assets/05e5cb3b-b567-4036-912e-fcf11dd5edca" />

 5. Switch Back to Main Branch

git checkout main

<img width="940" height="678" alt="image" src="https://github.com/user-attachments/assets/6d39505f-b0e9-4592-82f4-4eeda578306e" />

6. Merge Feature Branch into Main

git merge feature-update

<img width="940" height="175" alt="image" src="https://github.com/user-attachments/assets/8b004391-deba-4bbf-8081-0e7ab507403d" />

7. Verify Changes Are Merged

git log --oneline

<img width="774" height="59" alt="image" src="https://github.com/user-attachments/assets/bba823c8-3308-4bc7-b24b-d7f6c7de407d" />

8. Delete the Branch Safely

git branch -d feature-update

<img width="731" height="231" alt="image" src="https://github.com/user-attachments/assets/a9e0f70d-8027-42bc-afe3-97c0a1c200cc" />

9. Force Delete a Branch (Using Dummy Branch)

Create dummy branch:

git checkout -b temp-branch

<img width="702" height="195" alt="image" src="https://github.com/user-attachments/assets/410a59e2-9549-4419-8be7-9b3ad7579c97" />

Switch back to main and Force Delete:

git checkout master
git branch -D tempbranch

<img width="702" height="236" alt="image" src="https://github.com/user-attachments/assets/afcbff45-6032-452f-874d-f92dfd6dad28" />


