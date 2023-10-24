# hu26
import random 
print("Hey folks")
print("This is a kollyowod director game")
name=input("What's your name?")
print("Welcome to the game "+name)
print("Choose your genre of movies you like")
d=int(input("1.Action\n2.Romcom\n3.Fantasy\n4.Periodic\n5.Scifi\n6.Horror"))
if(d<=6):
  print(d+"That's a great choice")
else:
  print("Invalid choice")
print("The Kollywood director who can direct your lifetime story is")
if(d==1):
  a=['Lokesh kanagraj','Vetri maran','Hari']
  rand_a = random.choice(a)
  print(rand_a)
elif(d==2):
  b=['Vignesh shivn','Goutham Vasudev menon','Mani ratnam']
  rand_b = random.choice(b)
  print(rand_b)
elif(d==3):
  c=['Selvaragahavan','Ark Saravan','Gokul']
  rand_c = random.choice(c)
  print(rand_c)
elif(d==4):
  q=['Mani ratnam','Vetri maran','Kamal Hassan']
  rand_q = random.choice(q)
  print(rand_q)
elif(d==5):
  e=['Vikram kumar','Ravi kumar','Sakthi soundar rajan']
  rand_e = random.choice(e)
  print(rand_e)
else(d==6):
  f=['Raghava lawrence','Ram kumar','Sundar.c']
  rand_f = random.choice(f)
  print(rand_f)
