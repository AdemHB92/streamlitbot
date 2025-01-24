# streamlitbot
projet chatbot 
Adem HAJ BOUBAKER
Nacir JAZA
Mohamed Dhia ZELLAMA


cd Documents/git
mkdir projet_chatbot
cd projet_chatbot
git init
git clone https://github.com/AdemHB92/test.git
git status
git add .
git commit -m "initial commit"
git status
git remote -v
git remote add origin https://github.com/AdemHB92/test.git
git push origin master ( pour votre cas c'est main je pense!)
cd streamlitbot
python -m venv stenv
source stenv/Scripts/activate 
touch .gitgnore
nano .gitgnore 
#ajoutez les lignes suivantes et sauvegardez le fichier.
(# Python venv 
stenv

.gitignore)
enregistre et quitte (CTRL + O, puis CTRL + X)
touch requirements.txt
nano requirements.txt
( Ajoutez la bibliothéque streamlit)


pip install -r requirements.txt
streamlit hello (fonctionne bien)
git branch version1

git checkout version1 

touch chatbot.py
nano chatbot.py
(copier coller le code fournit de votre part)

streamlit run chatbot.py

git status
git add .
git commit -m "premiere version de mon chatbot"
git status
git push origin version1

git checkout main
git merge version1
-------------------------------
git branch version2
git checkout version2
nano chatbot.py
(ajouter le nouveau code)
streamlit run chatbot.py
git status
git add .
git commit -m "deuxieme version de mon chatbot"
git status
git push origin version2
git checkout main
git merge version2
----------------------------
git branch version3
git checkout version3
nano chatbot.py
(ajouter le nouveau code)
streamlit run chatbot.py
git status
git add .
git commit -m "deuxieme version de mon chatbot"
git status
git push origin version3
git checkout main
git merge version3
-------------------------------
1. touch chatbotgpt.py
2 . nano requirements.txt
pip install -r requirements.txt
3. mkdir .streamlit
4.cd .streamlit
touch secrets.toml
5.nano secrets.toml
6. cd ..
nano .gitgnore
8. 
git branch version4
git checkout version4
nano chatbotgpt.py
git add . 
git commit -m ""
git status
git push origin version4
git checkout main
git merge version4
streamlit run chatboxgpt.py
9.
git branch version5
git checkout version5
nano chatbotgpt.py
git add . 
git commit -m ""
git status
git push origin version5
git checkout main
git merge version5
streamlit run chatboxgpt.py

git branch selectbox
git checkout selectbox
nano chatbotgpt.py
git add . 
git commit -m ""
git status
git push origin selectbox
git checkout main
git merge selectbox
streamlit run chatboxgpt.py

git branch slider
git checkout slider
nano chatbotgpt.py
git add . 
git commit -m ""
git status
git push origin slider
git checkout main
git merge slider
streamlit run chatboxgpt.py

