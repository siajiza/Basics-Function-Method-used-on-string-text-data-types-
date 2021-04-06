<h1>Basics Function/Method used on string text data types</h1>

Description of variable´s content

    sentence = 'The quick brown fox jumped'
    ________________________________________
    sentence -> variable
    = -> assignment
    'The quick brown fox jumped' -> string
    ________________________________________


<h2>STRINGS METHOD</h2>

    sentence_one = 'The quick brown fox jumped' 
    print(sentence_one)  
    The quick brown fox jumped
    
<h4>str.upper()</h4>
Return a copy of the string with all the cased characters [4] converted to uppercase. 
Note that s.upper().isupper() might be False > if s contains uncased characters or if the Unicode category of the resulting character(s)
is not “Lu” (Letter, uppercase), but e.g. > “Lt” (Letter, titlecase).

    sentence_two = sentence.upper()                                    
    print(sentence_two)
    THE QUICK BROWN FOX JUMPED
    
<h4>str.capitalize()</h4>
Return a copy of the string with its first character capitalized and the rest lowercased.

    sentence_three = 'the quick brown fox jumped'.capitalize()          
    print(sentence_three)  
    The Quick Brown Fox Jumped

<h4>str.title()</h4>
Return a copy of the string with the first character, of the first word of the total sentence, to a  capital letter.

    sentence_four = 'the quick brown fox jumped'.title()
    print(sentence_four)
    The quick brown fox jumped
    
<h4>str.lower()</h4>
Return a copy of the string with all the cased characters [4] converted to lowercase.
    sentence_five = 'the Quick Brown fOx jumped'
    print(sentence_five.lower())
    the quick brown fox jumped
    


