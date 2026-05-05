
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

<img width="940" height="319" alt="image" src="https://github.com/user-attachments/assets/7478de69-093d-447f-a1bf-78dcb4adf8a4" />

5. Commit Changes with Clear Message

git commit -m 'Feature added'

<img width="940" height="260" alt="image" src="https://github.com/user-attachments/assets/e0d5d3fb-ffbf-4730-a9f1-160f421b561b" />

6. Make Another Change in `app.py`

print('Dev1')
print('Dev2')

<img width="940" height="176" alt="image" src="https://github.com/user-attachments/assets/d7cda62a-8f2b-46f4-a952-8c9b9181e7e3" />

7. Stage All Changes

git add .

<img width="940" height="206" alt="image" src="https://github.com/user-attachments/assets/4308263c-f71d-4d65-8f94-d265a9df0128" />

8. Commit Again

git commit -m 'DEV added' 

<img width="683" height="134" alt="image" src="https://github.com/user-attachments/assets/fe3f7817-eec9-476b-9de3-3708813e4627" />

9. View Full Commit History

git log

<img width="863" height="325" alt="image" src="https://github.com/user-attachments/assets/dbc6e134-165b-4b3c-a5c6-75c0b7d0feca" />

10. View Compact (One-Line) History

git log --oneline

<img width="355" height="68" alt="image" src="https://github.com/user-attachments/assets/a3ede414-dc06-4e61-bc90-82811f71dd55" />

