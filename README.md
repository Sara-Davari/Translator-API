# Translator-API
This API project combines STT and Speech Recognition to translate several sentences from any language to one chosen by the user for each sentence specifically. STT translation projects pose a difficult challenge as many languages like Chinese and Japanese are difficult for the program to understand, leading to translation mistakes.
Input: Sentence spoken and translation language chosen by the user.

Output: Sentence translated and the language shown

How it works:
1. Importing speech_recognition and deep_translator
2. Asking the user for the language they want their sentence translated to
3. Asking the user for how long they want to speek
4. Recording their sentence
5. Translating the sentence and displaying it along with the language it's translated to
6. The action is repeated 5 times using a loop asking the user whether they want to translate another sentence every time
7. Should the user type "no" anytime, the loop will stop

Results: The program translates sentences to common languages without mistakes, though difficult languages like Chinese or native dialects of languages take longer to translate and the translation is less accurate.

What I learned:
1. How to use API and its relevant libraries
2. How to create a STT program
3. How to mix STT and translator programs

Future developements:
1. Adding TTS to the program
2. Using more accurate libraries to lessen mistakes in uncommon languages
