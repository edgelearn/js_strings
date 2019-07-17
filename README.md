# JavaScript Strings

See https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String if you get stuck on any of these exercises.

1. String construction

* Create two string variables with quotes.

* Create a string variable using the String object.

2. String.charAt

* Perform a console.log of the third character in one of the strings constructed.

3. String.charCodeAt

* Perform a console.log of the second character code in one of the strings constructed.

4. String.concat

* Perform a console.log of the join of the two strings constructed.

5. String.endsWith

* Do a check for one of the strings constructed where endsWith returns true.

* Do a check for one of the strings constructed where endsWith returns false.

6. String.fromCharCode

* Perform a console.log of several character code numbers to their UTF-16 equivalent.

7. String.includes

* Do a check for one of the strings constructed where includes returns true.

* Do a check for one of the strings constructed where includes returns false.

8. String.indexOf

* Do a check for one of the strings constructed where indexOf returns a positive number.

* Do a check for one of the strings constructed where indexOf returns -1.

9. String.lastIndexOf

* Do a check for one of the strings constructed where lastIndexOf returns a positive number.

* Do a check for one of the strings constructed where lastIndexOf returns -1.

10. String.localeCompare

* Use localeCompare to compare the two strings constructed previously.

11. String.match

* Do a match against one of the strings with the regex /[A-Z]/g

12. String.repeat

* Use repeat with one of the strings to have it repeat 5 times.

13. String.replace

* Replace part of one of the strings using replace function.

14. String.search

* Search for part of one of the strings that returns an index.

* Search for part of one of the strings that returns -1.

15. String.slice

* Use the slice function to get the 4th through 8th characters in one of the strings.

16. String.split

* Use the split function to split a string by the space character.

17. String.startsWith

* Run startsWith for one of the strings that returns true.

* Run startsWith for one of the strings that returns false.

18. String.substring

* Use the substring function to get the 4th through 8th characters in one of the strings.

19. String.toLocaleLowerCase

* Use toLocaleLowerCase on one of the strings previously created.

20. String.toLocaleUpperCase

* Use toLocaleUpperCase on one of the strings previously created.

21. String.toLowerCase

* Use toLowerCase on one of the strings previously created.

23. String.toString

* Use toString on the string object created in the first step.

24. String.toUpperCase

* Use toUpperCase on one of the strings previously created.

25. String.trim

* Use trim on one of the strings previously created.

26. String.valueOf

* Use valueOf on the string object created in the first step.

27. RegEx examples

Digits:

* Whole Numbers – /^\d+$/
* Decimal Numbers – /^\d*\.\d+$/
* Whole + Decimal Numbers – /^\d*(\.\d+)?$/
* Negative, Positive Whole + Decimal Numbers – /^-?\d*(\.\d+)?$/
* Whole + Decimal + Fractions – /[-]?[0-9]+[,.]?[0-9]*([\/][0-9]+[,.]?[0-9]*)*/

Alphanumeric Characters:

* Alphanumeric without space – /^[a-zA-Z0-9]*$/
* Alphanumeric with space – /^[a-zA-Z0-9 ]*$/

Date Format:

* YYYY-MM-dd - /([12]\d{3}-(0[1-9]|1[0-2])-(0[1-9]|[12]\d|3[01]))/

Time Format:

* HH:MM 12-hour, optional leading 0 - /^(0?[1-9]|1[0-2]):[0-5][0-9]$/
* HH:MM 12-hour, optional leading 0, Meridiems (AM/PM) - /((1[0-2]|0?[1-9]):([0-5][0-9]) ?([AaPp][Mm]))/

After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "JS Strings Examples"
```
