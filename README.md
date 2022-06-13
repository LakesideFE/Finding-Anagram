# Finding-Anagram

def find_anagram(word, anagram):
    # [assignment] Add your code here
    if(sorted(word) == sorted(anagram)):
        print(sorted(word), sorted(anagram))     
        return True
    return False
print(find_anagram('break', 'brake'))
print(find_anagram('break', 'broke'))
