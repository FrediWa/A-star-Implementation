This is the second project of the course "Datastrukturer och algoritmer" (Datastructures and algorithms). The purpose of it was to, using the A* algorithm, find the optimal path for a hypothetical delivery drone to take. The user inputs a starting location and a destination and the program gives the shortest path based on the weights(which in this case is calculated using a great circle distance calculation between the coordinates of each node's corresponding real world location. The assignment was done in pairs, my role was the implementation of the actual algorithm along with all necessary calculations.

The reason for the 1 "initial commit" commit is because the project was built on a private repo issued by our lecturer. 

# Projekt 1 - Ruttsökning

Vi märkte inte att det fanns en färdig repository så vi hamnade kopiera koden över från den vi började på.

## Del 1

Denna uppgift var lätt, jag satt in alla egenskaper som Noden behövde. createGraph metoden gjorde jag på ett kanske lite dummare sätt.

## Del 2

Gjorde en lista på nodernas grannar 
och sedan med hjälp av en nested 
for-loop där man loopar först
noderna och sedan varje nods grannar.

Skulle säga att det gick helt smärtfritt.

## Del 3

Det här var ju bara att copy/paste? Varför var den alls värd poäng? 

## Del 4

Här gick vi enligt pseudokoden, vilket
hjälpte mycket men vi hade lite problem
när vi kom till A* när F skulle räknas.

Dvs.  gjorde en while-loop var man kollar när
current blir samma som source. Då vet vi hur
lång sträcka det är från en viss nod till starten, 
genom att hoppa via andra noder.

## Del 5 
Jag tror att jag fick A* och fungera fullständigt. Jag berättar mer om vad jag gjorde under presentationen men kort sagt så skrev jag av Jonnys pseudo kod, rev ut hälften av mina hårstrån medan jag de-buggade i något som kändes som ett århundrade och till slut fick något och fungera då jag verkligen försökte förstå algoritmen och började ändra på Jonnys algoritm tills jag förstod vad som hände.
