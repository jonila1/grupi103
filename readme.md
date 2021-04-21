1.Konfigurimi
git config --global user.name "jonila1"
git config --global user.email "emaili"

2.E misim projektin, qe do te thote e krijojme pathin per ,e dergu ne github
  git init

  3.Ne nderkohe e hapni nje repository ne Github (name project, description)

  4. I vendosim te gjitha file qe po dojme me i dergu ne Github
    git add -A 
    git add readme.md /dergimi per file specifik

  5.Dergimi i mesazhit dhe commit
     git commit -m "your message"

6. I tregojme linkun (pathin) se ne cilin repositery ka me shku projekti ne Github
  git remote add origin https://github.com/jonila1/a39.git

7.Dergimi/Pushi
  git push origin master
8.nese deshirojme me pa ndryshimet ose modifikimet e filsve