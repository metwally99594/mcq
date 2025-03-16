# mcq# Create a new folder for your project
mkdir mcq-quiz
cd mcq-quiz

# Initialize Git and create README
echo "# MCQ Quiz Project" >> README.md
git init
git add README.md
git commit -m "Initial commit"

# Connect to GitHub
git remote add origin https://github.com/metwally99594/mcq.git
git branch -M main
git push -u origin main
