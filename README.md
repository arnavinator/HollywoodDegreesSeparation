# HollywoodDegreesSeparation

Using IMBd database, use Breadth-First uninformed search to calculate degrees of separation.  
User inputs name of 2 Hollywood actors, program outputs and calculates their relationship (if any).  

util contains node data structure, and queue first-in last-out frontier  
large contains information on all actors, small used for testing/debugging  

Usage in terminal:  
python degrees.py large  
Loading data...  
Data loaded.  
Name: Emma Watson  
Name: Jennifer Lawrence  
3 degrees of separation.  
1: Emma Watson and Paul Rudd starred in The Perks of Being a Wallflower  
2: Paul Rudd and Michelle Pfeiffer starred in I Could Never Be Your Woman  
3: Michelle Pfeiffer and Jennifer Lawrence starred in Mother!  
