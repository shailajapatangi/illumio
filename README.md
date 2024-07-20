How to run this program?

java -jar [absolute path of the jar, refer screenshot_cmd] on command prompt

For input and predefined files, enter absolute paths

Assumption.

1. Matching is case insensitive i.e if the word is 'detect' and the predefined word is 'Detect', they are matched
2. The words with and without 's are treated different. For example your's id different from your
3. Words containing special characters such as #wedding is different from wedding. #wedding is matched with only #weding.
4. Similarly the case with @, %, $, &, *, (, ), ^, -,= , <,>, {,}, ", '
5  The special characters such as  :, ;, !, /, ?, |, +, . , , , are treated as separators. Wedding: is matched with wedding.

Testing:

1. Tested for given input in the example
2. Tested with 20mb input file
3. Tested with sentences containing special characters such as :, ;, !, /, ?, |, +, . , , ,
4. Tested with predefined word of 256 characters
5. Tested with words containing 's, matter's is different from matter.
