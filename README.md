# anagrams-s
def find_anagram(word, anagram):
    def check(s1,s2):
         
    
    if(sorted(s1)== sorted(s2)):
        print("The strings are anagrams.")
    else:
        print("The strings aren't anagrams.")        
         
# driver code 
s1 ="basiparachromatin"
s2 ="marsipobranchiata"
check(s1, s2)
