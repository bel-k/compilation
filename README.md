# compilation
 # TD1
 #  Exercices 1 & 2
déjà fait en classe
#  Exercices 3 
#  Question 1.
Donner une expression régulière ainsi qu'un automate déterministe qui représentent les langages suivants :
# 
# a)
L = { m | m ∈ {a, b}* et m contient ‘ba’ comme sous-mot }

![image](https://user-images.githubusercontent.com/95535082/167314374-ba4979ef-aa25-4e74-a2bc-db7e85fd2d6d.png)
# 
# b)
L = { m | m ∈ {a, b, c}* et m commence par un ‘a’ et se termine par ‘bc’ }

![image](https://user-images.githubusercontent.com/95535082/167314327-4b5b229b-ca15-4f51-9336-845bb9b9a1da.png)
# 
# c)
L = { m | m ∈ {a, b}* et m ne contient PAS un nombre de ‘b’ égal à 2 }

![image](https://user-images.githubusercontent.com/95535082/167314227-b12ea1a0-f987-4660-b648-e9c2a6cb2275.png)
# 
# d)
L = { m | m ∈ {a, b}* et m contient un nombre de ‘b’ égal à 2 }

![image](https://user-images.githubusercontent.com/95535082/167314487-fa7176c0-79ac-48bc-9eff-0447ab1e8ac3.png)
# 
# e)
L = { m | m ∈ {a, b}* et m se termine par ‘bab’ OU ‘bb’ }

![image](https://user-images.githubusercontent.com/95535082/167314623-51693b5f-7e4c-4632-85bd-4905b3f0db82.png)
# 
# f)
L = { m | m ∈ {a, b}* et m contient au plus 2 ‘a’ et au moins 2 ‘b’ }

![image](https://user-images.githubusercontent.com/95535082/167315128-df54a7f0-5716-4b67-b312-cc1009982b80.png)
# 
#  Question2.
Ecrivez une expression régulière sur l’alphabet Σ = {a, b, c} dont le langage associé est
exactement l’ensemble des mots ou a est toujours suivi de b et b est toujours suivi de a, sauf
éventuellement pour le dernier symbole du mot.

---> expression régulière :c*(b|(a|ba)(ba)*b)

![image](https://user-images.githubusercontent.com/95535082/167315336-82477b7c-bfd1-4f44-a5b7-6fdaa9876a55.png)
# 
#  Question3.
Ecrivez une expression régulière sur l’alphabet Σ = {a, b} dont le langage associé est
exactement l’ensemble des mots qui ne contiennent jamais deux a consécutifs.

---> expression régulière :((b*|a)b)*
![image](https://user-images.githubusercontent.com/95535082/167315713-10f6bcf7-c7ac-4e81-9098-3cd8d28e221d.png)
# 
#  Question4.
Est-ce que les expressions régulières suivantes contiennent le mot vide ε ?

1)
(a+ba∗)∗+b(a+ (b+aba)∗)∗---------------->  non

2)
(1 + b)(aa∗+bb∗a)∗---------------------->  oui


3)
(1 + a)(1 + b)(1 + c)(1 + d)(e+f)------>  non

4)
(a+ (b+ (c+d)∗)∗)∗---------------------->  oui

#  Exercices 4
Soit A = {a, b, c}. Pour chacun des langages suivants, donner un automate fini
déterministe (AFD) le reconnaissant :
# 
# a)
l’ensemble des mots dont la longueur est un multiple de 3 

![image](https://user-images.githubusercontent.com/95535082/167316057-a13d164a-0ff0-4c7b-b773-3deb70b173fe.png)

# 
# b)
l’ensemble des mots dans lesquels chaque occurrence du motif ab (s’il y en a), est suivie
de ccc

![image](https://user-images.githubusercontent.com/95535082/167316217-89d5d09c-7422-45bf-ae79-a145136f8445.png)
# 
# C)
l’ensemble des mots se terminant par b ;

![image](https://user-images.githubusercontent.com/95535082/167316305-0a9640fc-c533-4a0d-ba85-af2e2426ae45.png)

# 
# d)
l’ensemble des mots ne se terminant pas par b 

![image](https://user-images.githubusercontent.com/95535082/167316544-6a57ebde-e672-4617-991e-8c3af525abab.png)

# 
# e)
l’ensemble des mots contenant exactement un b

![image](https://user-images.githubusercontent.com/95535082/167316648-502e5d87-3594-4dd9-b6f7-bc19cf0284f4.png)

# 
# f)
l’ensemble des mots ne contenant aucun b ;

![image](https://user-images.githubusercontent.com/95535082/167316725-e522056d-24ff-465f-ad13-0cc9786bc7a3.png)

# 
# h)
l’ensemble des mots comportant au moins 3 lettres et dont la troisième lettre à partir de la fin est un a ou un c

![image](https://user-images.githubusercontent.com/95535082/167316994-fc67f3ef-b86b-4e6b-84b3-63946ab32742.png)

# 
#  Exercices 5
Déterminiser l’automate

![image](https://user-images.githubusercontent.com/95535082/167317683-99d0c5bb-0593-4997-a12b-44313c0e875a.png)

# 
#  Exercices 6
Construire l’automate fini correspondant aux expressions régulières suivantes.
# 
# a) 
(a + b)*c

![image](https://user-images.githubusercontent.com/95535082/167317750-67118718-629f-4809-a22a-50528f5b7610.png)
# 
# b) 

a* (ε + bb)a + ε


![image](https://user-images.githubusercontent.com/95535082/167317936-6abc5c9a-ca74-4e44-b4bd-a3487ee9ae14.png)

