Τα περισσότερα από τα templates μπορούν να λειτουργήσουν και με τα ελληνικά αρκεί να προσθέσετε τις ακόλουθες γραμμές στο preample του αρχείου (μαζί με τα υπόλοιπα usepackage δηλαδή):

%Aparaitita paketa gia ellinika
\usepackage{xltxtra} 
\usepackage{xgreek} 
%I poly kali grammatoseira GFS Didot pou kanoun ta ellinika na miazoun stin grammatoseira tou LaTeX
\setmainfont[Mapping=tex-text]{GFS Didot} 

Προσοχή: Χρειάζεται να έχετε εγκατεστημένη την πλήρη έκδοση του LaTeX δηλαδή το texlive-full. 
Μπορείτε στις διανομές ubuntu να το εγκαταστήσετε πατώντας στο τερματικό: sudo apt-get install texlive-full

Τέλος θα πρέπει να κάνετε compile το αρχείο με το XeLaTeX και όχι με το PDFLaTeX!

%---------------------------------------------------------------------------------

Σε ότι αφορά τις διαφάνειες, δυστυχώς δεν έχω βρεί κάποιο τρόπο μέχρι τώρα ώστε να γράφουμε ελληνικά και να μπορούμε να κάνουμε compile με το XeLaTeX. Ο μόνος τρόπος είναι να χρησιμοποιήσουμε το πακέτο Babel και γράφοντας ελληνικά με αγγλικούς χαρακτήρες (με άθλια αντιστοίχηση) να καταφέρουμε να παράγουμε το τελικό αποτέλεσμα. Για όσους ενδιαφέρονται, δείτε και το αντίστοιχο αρχείο στο φάκελο Slides.