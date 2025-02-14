# Week 4 Email
---

**Note:** There is a table of contents for each video at the bottom of this email including timestamps to where various content is located. This should be helpful in navigating the videos.

---

In this email of Learning Python we are going to cover the following:

   - Dictionaries<br>
   Video https://vimeo.com/246157566<br>
   Length is 6 minutes<br>

   - Dictionaries Methods<br>
   Video https://vimeo.com/246163031<br>
   Length is 7 minutes<br>

   - Sets<br>
   Video https://vimeo.com/246167477<br>
   Length is 9 minutes<br>

   - Exceptions<br>
   Video https://vimeo.com/246174686<br>
   Length is 15 minutes<br>

   - Regular Expressions (Part1)<br>
   Video https://vimeo.com/246184715<br>
   Length is 15 minutes<br>

   - Regular Expressions (Part2)<br>
   Video https://vimeo.com/246532117<br>
   Length is 7 minutes<br>

   - Regular Expressions (Part3)<br>
   Video https://vimeo.com/246534450<br>
   Length is 8 minutes<br>

   - Regular Expressions, Other Methods<br>
   Video https://vimeo.com/246535038<br>
   Length is 4 minutes<br>

# Additional Content:

- [Regular Expression Tutorial](https://t.dripemail2.com/c/eyJhY2NvdW50X2lkIjoiNDI1NDQ5NyIsImRlbGl2ZXJ5X2lkIjoiMHNnMjhwbTUwdmhlNWw3bW55YjQiLCJ1cmwiOiJodHRwczovL3JlZ2V4b25lLmNvbS9sZXNzb24vaW50cm9kdWN0aW9uX2FiY3M_X19zPWxreGEzOGhsMHZwc3dxdDM4aWQ2In0) This is a good resource if you are new to regular expressions.

- [Online Regular Expression Tester](https://t.dripemail2.com/c/eyJhY2NvdW50X2lkIjoiNDI1NDQ5NyIsImRlbGl2ZXJ5X2lkIjoiMHNnMjhwbTUwdmhlNWw3bW55YjQiLCJ1cmwiOiJodHRwczovL3JlZ2V4MTAxLmNvbS8_X19zPWxreGEzOGhsMHZwc3dxdDM4aWQ2In0) Select 'Python' on the left-hand side.

- [Python Regular Expression HowTo](https://t.dripemail2.com/c/eyJhY2NvdW50X2lkIjoiNDI1NDQ5NyIsImRlbGl2ZXJ5X2lkIjoiMHNnMjhwbTUwdmhlNWw3bW55YjQiLCJ1cmwiOiJodHRwczovL2RvY3MucHl0aG9uLm9yZy8yL2hvd3RvL3JlZ2V4Lmh0bWw_X19zPWxreGEzOGhsMHZwc3dxdDM4aWQ2In0) This is a good overview of regular expression special characters.  Start at the very top of the page and read through the 'Repeating Things' section.

- [Automate the Boring Stuff - Dictionaries and Structuring Data​](https://t.dripemail2.com/c/eyJhY2NvdW50X2lkIjoiNDI1NDQ5NyIsImRlbGl2ZXJ5X2lkIjoiMHNnMjhwbTUwdmhlNWw3bW55YjQiLCJ1cmwiOiJodHRwczovL2F1dG9tYXRldGhlYm9yaW5nc3R1ZmYuY29tL2NoYXB0ZXI1Lz9fX3M9bGt4YTM4aGwwdnBzd3F0MzhpZDYifQ) Read through the 'The GET() Method' section.

---

# GitHub.com: Kirk Byers
Reference code for these exercises is posted on GitHub at:
https://github.com/ktbyers/pynet/tree/master/learning_python/lesson4

---

# CLASS OUTLINE

- Dictionaries (VIDEO1)
   - What is a dictionary?   [0:03]
   - Why do we need dictionaries?   [0:40]
   - How to create a dictionary   [1:33]
   - Adding keys to a dictionary   [1:58]
   - Using variables as keys   [2:52]
   - Accessing keys in a dictionary   [4:00]
   - Accessing keys that don’t exist   [4:32]
   - Dictionaries are mutable   [5:05]
- Dictionary Methods (VIDEO2)
   - get() method   [0:34]
   - copy() method   [2:23]
   - pop() method for key removal   [3:01]
   - update() method   [3:49]
   - Looping over dictionaries   [5:04]
   - Using .values()   [5:32]
   - Using .items()   [6:01]
- Sets (VIDEO3)
   - What is a set?   [0:04]
      - Each element has to be unique
      - Sets are unordered
      - No indices
   - Looping over a set   [2:00]
   - Set operations   [2:23]
      - Union   [2:39]
      - Intersection   [3:33]
      - Difference   [4:11]
      - Symmetric diff   [5:53]
- Exceptions (VIDEO4)
   - Example exception   [0:19]
   - Non-zero exit status   [2:22]
   - Using try/except   [2:38]
   - Catching an exception and re-raising   [6:33]
   - Catching an exception and printing   [8:22]
   - Catching multiple exceptions   [9:34]
   - Adding a finally clause   [12:00]
- Regular Expressions (Part1) (VIDEO5)
   - Why we need regex?   [0:05]
   - Some special characters   [1:24]
      - Any single character: . [1:33]
      - One or more times: +   [4:54]
      - Zero or more times: *   [5:56]
      - Beginning of line: ^   [6:37]
      - End of line: $   [6:55]
      - Digit character class: \d   [7:30]
      - Whitespace character class: \s   [9:29]
      - Non-whitespace: \S   [10:20]
      - Construct your own character class: []   [11:11]
      -. Parenthesis to save things: ()   [12:23]
   - By default will be greedy.   [5:35]
- Regular Expressions (Part2) (VIDEO6)
   - Why you always use raw strings   [0:04]
   - Using re.search()   [1:21]
      - Arguments   [2:06]
      - If successful, match object   [2:30]
         - match.group(0)   [2:34]
         - match.group(1)   [3:48]
   - Constructing named patterns   [4:55]
      - match.groupdict()   [5:55]
- Regular Expressions (Part3) (VIDEO7)
   - Disabling greedy behavior   [0:31]
   - Flags to re.search   [3:02]
      - re.M  [4:58]
      - re.DOTALL   [6:50]
      - re.I   [7:41]
- Regular Expressions, Other Methods (VIDEO8)
   - re.split()   [0:14]
   - re.sub()   [1:48]
   - re.findall()   [3:38]
