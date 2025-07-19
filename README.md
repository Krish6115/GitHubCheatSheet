# GitHubCheatSheet
📦 Scenario: Uploading a file to a GitHub repo

Example:

GitHub Username: Krish6115

Repo Name: LeetCode

Target Folder in Repo: LinkedList

File to Upload: InsertLinkedList.java

🧱 STEP 1: Clone the Repository (Only Once)

bash

git clone https://github.com/Krish6115/LeetCode.git

cd LeetCode

📂 STEP 2: Move your file into the correct folder

bash

move /path/to/InsertLinkedList.java LinkedList/

Or manually drag the file into the folder using VS Code

✅ STEP 3: Stage the file

bash

git add LinkedList/InsertLinkedList.java

📝 STEP 4: Commit the changes

bash

git commit -m "Added InsertLinkedList.java to LinkedList folder"

🚀 STEP 5: Push the changes to GitHub

bash

git push origin main

If your repo uses master branch, use:

bash

git push origin master

⚙️ FIRST-TIME ONLY: Set Git Identity (If prompted)

bash

git config --global user.name "Krish6115"

git config --global user.email "your-email@example.com"

Replace with your real GitHub email

🧯 IF ERROR: "Updates were rejected" (remote has newer commits)

bash

git pull origin main --rebase

Then push again:

bash

git push origin main

🔁 For Every New File (after initial setup)

Just repeat these three:

bash

git add path/to/yourfile.java

git commit -m "Your commit message"

git push origin main
