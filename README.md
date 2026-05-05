1. Make Changes to `app.py` (Do NOT Commit)

<img width="592" height="191" alt="image" src="https://github.com/user-attachments/assets/1e485dc6-966a-46ec-b055-fdbbe2c50748" />

2. Stash Changes (Including Untracked Files)

git stash 

<img width="940" height="120" alt="image" src="https://github.com/user-attachments/assets/5206ae0c-3597-4fbe-be29-3f48d8d11b1d" />

3. Check Stash List

git stash list

<img width="713" height="134" alt="image" src="https://github.com/user-attachments/assets/11916d45-9490-45e7-9999-60885aa33548" />

4. Apply Stashed Changes Back

git stash pop

<img width="852" height="341" alt="image" src="https://github.com/user-attachments/assets/5dfc14b6-20f5-4af2-97db-2554dd92ddfc" />

5. Stage and Commit Changes

git add .
git commit -m "Application 1 & 2 added"

<img width="927" height="141" alt="image" src="https://github.com/user-attachments/assets/658f9a09-fcc4-4815-b3d0-84c619bd9536" />

Reset Example (Undo Last Commit)

6. Make Another Commit (Incorrect Code)

print('Bug code 1')
print('Bug code 2')
git add app.py
git commit -m "Bug code added"

<img width="841" height="244" alt="image" src="https://github.com/user-attachments/assets/ea23bc08-870e-4fd0-ab9b-2110b885ad4c" />

7. Undo Last Commit Using Reset

Soft Reset (keep changes staged)

<img width="716" height="86" alt="image" src="https://github.com/user-attachments/assets/6447cdbe-9ac6-4415-af17-ba6aae353dae" />

git reset --soft HEAD~1

<img width="655" height="111" alt="image" src="https://github.com/user-attachments/assets/21136eba-47eb-4ad5-a144-1ddf89714b92" />

<img width="742" height="239" alt="image" src="https://github.com/user-attachments/assets/a4c8c03d-6d08-4ef3-acf2-ea3515896a17" />

Revert Example 
8. Make Another Commit

print('Store 1')
print('Store 2')

git add app.py
git commit -m "Store added"

<img width="703" height="134" alt="image" src="https://github.com/user-attachments/assets/15a1946c-86c4-4afd-b46e-abf2ab0eb041" />

9. Undo Using Revert (Safe Method)

<img width="578" height="91" alt="image" src="https://github.com/user-attachments/assets/36224b70-a8c1-44ce-a1c1-6f34ae81d045" />

git revert HEAD

<img width="656" height="94" alt="image" src="https://github.com/user-attachments/assets/c25ea155-fbd3-4316-80e8-3be0d3644cfe" />

10. Verify Commit History

git log --oneline

<img width="469" height="88" alt="image" src="https://github.com/user-attachments/assets/3e4baa13-c077-42aa-ac8c-a5163a4fcb08" />

