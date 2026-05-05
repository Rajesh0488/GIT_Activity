
1. Modify `app.py`

print('Feature-1')
print('Feature-2')

<img width="940" height="164" alt="image" src="https://github.com/user-attachments/assets/9a85a1f6-bd36-4a2f-a6ba-e391dcb8a851" />

2. Check Changes Before Staging

git status

<img width="940" height="271" alt="image" src="https://github.com/user-attachments/assets/35d1921b-8220-4b07-9a16-bee414f2f1c7" />

 3. View Differences (Unstaged Changes)

git diff

<img width="844" height="325" alt="image" src="https://github.com/user-attachments/assets/e8cbf27b-8193-42bb-a5ea-26b3bfb46ec7" />

4. Stage Specific Changes (Partial Staging)

git add -p app.py

<img width="940" height="260" alt="image" src="https://github.com/user-attachments/assets/cd666229-31c5-4499-a767-6f8df84e96de" />

5. Commit Changes with Clear Message

git commit -m 'Feature added'

<img width="940" height="176" alt="image" src="https://github.com/user-attachments/assets/f0d1050c-d4f0-4fc2-9bd0-06019b17e603" />

6. Make Another Change in `app.py`

print('Dev1')
print('Dev2')

<img width="940" height="206" alt="image" src="https://github.com/user-attachments/assets/6e19a978-664b-4a9e-a75f-0712262b91f0" />

7. Stage All Changes

git add .

<img width="683" height="134" alt="image" src="https://github.com/user-attachments/assets/f218bafd-7738-4dec-90f9-127a11d2647b" />

8. Commit Again

git commit -m 'DEV added' 

<img width="863" height="325" alt="image" src="https://github.com/user-attachments/assets/d2e72ff6-e323-43f0-b0e7-518eba492e19" />

9. View Full Commit History

git log

<img width="555" height="106" alt="image" src="https://github.com/user-attachments/assets/8dacba30-fe94-4ab2-9c3b-5b05b81bdd87" />

10. View Compact (One-Line) History

git log --oneline

![Uploading image.png…]()
