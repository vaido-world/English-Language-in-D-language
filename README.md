# English-Language-in-D-language
A journey around English language using D language to explain and show things.
https://run.dlang.io/
```
import std;
void main()
{
    writeln("String is a string of a characters literals.");
    writeln("String is also known as a word in English language.");
    
    alias dictionary = vocabulary;
    string[] vocabulary;
    writeln(newline, "A static array variable is being initialized.");
    
    alias alphabet = letters;
    char[26] letters = ['a','b', 'c', 'd', 'e', 
                        'f', 'g', 'h', 'i', 'j', 
                        'k', 'l', 'm', 'n', 'o', 
                        'p', 'q', 'r', 's', 't', 
                        'u', 'v', 'w', 'x', 'y', 'z'];
    
    writeln("The static array contains ", letters.array.length, " values of char type");
   
    writeln(newline, "A foreach loop is being used to write out each letter in the static array.");
    foreach(letter; letters){
    	write(letter);
    } writeln;
    
    foreach(letter; alphabet){
    	write(letter);
    } writeln;
    
    writeln;
    writeln("A word is a junction of letters seperated by a space symbol.");
    writeln("  Example of a word: Book", " The word Book is part of English language vocabulary.");
    
    writeln(newline, "Vocabulary is an interface to human language.");
    writeln(newline, "The standartisation of words is called a Vocabulary");
    writeln("A vocabulary explains other more complex words by using basic real world words.");
    
    writeln(newline, "That's is how vocabulary is built.");
    writeln("By building on blocks of pre-exposed pre-existing words shown in real world situations.");
    
    writeln(newline, "Training of the most basic words include: exposure and events analysis");
    writeln("By guidance and reflections of the meaning of words in motions and disclosure");
    
    writeln(newline, "The example of training: ", "pointing with a finger and drawing with a finger around the edges to show the edges of the object.");
    writeln(newline, "The example of training: ", "Showing actions using body parts and request of repetition by showing excitement (quick sudden motions as approval).");
    writeln(newline, "The example of training: ", "Pointing at objects with a finger.");
    
    writeln(newline, "A Regex will be used to recognize the words.");
    
    writeln;
    char[1] fullstop = '.';
    writeln("A sentence is just a junction of words that end in full stop symbol");
	writeln("The full stop symbol: ", fullstop, " is also known as period and full point symbol.");
    
    writeln("Notice: If a sentence does not include a full stop at the end of the sentence. (which is: last word),");
    writeln("the word is not considered a sentence. And only implicitly stated by those that interpret the language.");
    writeln("  Example of a word: ", "Human.");
    
    writeln("Notice: If it is a single word sentence, space symbol is not required and is optional.");
    writeln("  Example of a word: ", "Human.");
    
    
    writeln;
    writeln("Hello D");
}
```
