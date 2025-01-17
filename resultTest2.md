# 📖 Notes :
Some text colors in the ui needs minor adjustments to enhance the readability of the content (make text a bit darker) for example:
  - assignment model in the see-more for the member
  - sessions ui in the member section more styling can be done to make the page visually pleasant for our members 

## 🌟 Le nom du contributeur : Ghassen Latrach 

## 📁 Lieux de l'erreur :
 logout method-authstore.tsx : error messege related to mis-use of client-side components , it may be the window.href

interface Instructor - interface member - auth

## 📊 type d'erreurs :

Front-end:
- session form , inputs are not positioned correctly must adjust their container(styling) and make it responsive as well 
- in the mobile vue (session crud/instructor) there is an "Error fetching instructors"
    2117-575a5be159c1cec9.js:1 Error fetching instructors: TypeError: s.setValue is not a function
    at x
- mobile vue button participate does Nothing (useless)
- crud session ( in the update cannot change the name of the instructor) 
- it would be better if the response placememnt changes after submitting the new status ( current state only changes after a page refresh )

Back-end - query of fetching instructors in the select (mobile) not working as well as updating session(change instructor in a particular session) 

## Image illustratif :
logout error :
[![Capture-d-cran-2025-01-17-122402.png](https://i.postimg.cc/sxcbsz03/Capture-d-cran-2025-01-17-122402.png)](https://postimg.cc/zHyxFsrQ)


