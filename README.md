# regex101.com/quiz
- Link https://regex101.com/quiz

# Description

This reposotory was inspired bye the [wiserookami/Regex101.com-Quiz-reference](https://github.com/wiserookami/Regex101.com-Quiz-reference)

These answers are from my origin, so perhaps there may be more efficient ways to solve each problem. So if you're going to use some RegExp here in production, I recommend researching more

	

## Reference ##

- [Task 1: Word Boundaries](#task-1-word-boundaries)
- [Task 2: Capitalizing I](#task-2-capitalizing-i)
- [Task 3: Uppercase Consonants](#task-3-uppercase-consonants)
- [Task 4: Retrieve Numbers](#task-4-retrieve-numbers)
- [Task 5: Whitespace](#task-5-whitespace)
- [Task 6: Broken Keyboard](#task-6-broken-keyboard)
- [Task 7: Validate an IP](#task-7-validate-an-ip)
- [Task 8: HTML Tags](#task-8-html-tags)
- [Task 9: Match an E-Mail](#task-9-match-an-e-mail)
- [Task 10: Followed by](#task-10-followed-by)
- [Task 11: Validate Floating Point Numbers](#task-11-validate-floating-point-numbers)
- [Task 12: Match any number between 0-100](#task-12-match-any-number-between-0-100)
- [Task 13: Match alternating 0s and 1s in any order](#task-13-match-alternating-0s-and-1s-in-any-order)
- [Task 14: Spam Filter](#task-14-spam-filter)
- [Task 15: Not Surrounded By Digits](#task-15-not-surrounded-by-digits)
- [Task 16: Repeated Words](#task-16-repeated-words)
- [Task 17: Start before End](#task-17-start-before-end)
- [Task 18: Every other digit](#task-18-every-other-digit)
- [Task 19: The Thousands](#task-19-the-thousands)
- [Task 20: Quoted Text With Escapes](#task-20-quoted-text-with-escapes)
- [Task 21: Replace Text, Not Code](#task-21-replace-text-not-code)
- [Task 22: Tokenized List](#task-22-tokenized-list)
- [Task 23: Replace In Between](#task-23-replace-in-between)
- [Task 24: Outermost brackets](#task-24-outermost-brackets)
- [Task 25: ababba](#task-25-ababba)
- [Task 26: Return of the brackets](#task-26-return-of-the-brackets)
- [Task 27: Shorten IPv6](#task-27-shorten-ipv6)
- [Task 28: aaabbbccc](#task-28-aaabbbccc)

## Task 1: Word Boundaries ##
        Question: Check if a string contains the word word in it (case insensitive). If you have no idea, I guess you could try /word/.

        RegExp: \bword\b
	

## Task 2: Capitalizing I ##
        Question: Use substitution to replace every occurrence of the word i with the word I (uppercase, I as in me). E.g.: i'm replacing it. am i not? -> I'm replacing it. am I not?. A regex match is replaced with the text in the Substitution field when using substitution.
        
        RegExp: /\bi\b/g
	
	Substitution: I
	

## Task 3: Uppercase Consonants ##
        Question: With regex you can count the number of matches. Can you make it return the number of uppercase consonants (B,C,D,F,..,X,Y,Z) in a given string? E.g.: it should return 3 with the text ABcDeFO!. Note: Only ASCII. We consider Y to be a consonant! Example: the regex /./g will return 3 when run against the string abc.
        
        RegExp: /(?![AEIOU])[A-Z]/g
	

## Task 4: Retrieve Numbers ##
        Question: Count the number of integers in a given string. Integers are, for example: 1, 2, 65, 2579, etc.
        
        RegExp: /\d+/g
	

## Task 5: Whitespace ##
        Question: Find all occurrences of 4 or more whitespace characters in a row throughout the string.
        
        RegExp: /\s{4}\s*/g
	

## Task 6: Broken Keyboard ##
        Question: 
        
        Solution:
	

## Task 7: Validate an IP ##
        Question: 
        
        Solution:
	

## Task 8: HTML Tags ##
        Question: 
        
        Solution:
	

## Task 9: Match an E-Mail ##
        Question: 
        
        Solution:
	

## Task 10: Followed by ##
        Question: 
        
        Solution:
	

## Task 11: Validate Floating Point Numbers ##
        Question: 
        
        Solution:
	

## Task 12: Match any number between 0-100 ##
        Question: 
        
        Solution:
	

## Task 13: Match alternating 0s and 1s in any order ##
        Question: 
        
        Solution:
	

## Task 14: Spam Filter ##
        Question: 
        
        Solution:
	

## Task 15: Not Surrounded By Digits ##
        Question: 
        
        Solution:
	

## Task 16: Repeated Words ##
        Question: 
        
        Solution:
	

## Task 17: Start before End ##
        Question: 
        
        Solution:
	

## Task 18: Every other digit ##
        Question: 
        
        Solution:
	

## Task 19: The Thousands ##
        Question: 
        
        Solution:
	

## Task 20: Quoted Text With Escapes ##
        Question: 
        
        Solution:
	

## Task 21: Replace Text, Not Code ##
        Question: 
        
        Solution:


## Task 22: Tokenized List ##
        Question: 
        
        Solution:


## Task 23: Replace In Between ##
        Question: 
        
        Solution:


## Task 24: Outermost brackets ##
        Question: 
        
        Solution:


## Task 25: ababba ##
        Question: 
        
        Solution:


## Task 26: Return of the brackets ##
        Question: 
        
        Solution:


## Task 27: Shorten IPv6 ##
        Question: 
        
        Solution:


## Task 28: aaabbbccc ##
        Question: 
        
        Solution:
	

