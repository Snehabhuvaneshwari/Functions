# Functions
word = input("enter the word: ").lower()
dict = {}
def letter(word):
  for x in word:
    key =dict.keys()
    if x in key:
      dict[x] + = 1
    else:
      dict[x] = 1
  print(dict)
letter(word)  
  
  
      
      
      
      

