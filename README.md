# We need your help!

Tidenes Kommune was made in a hurry, and so was the website.
DiFi has already noticed that it doesn't work very well for a lot of users and has threatened with fines unless fixed asap.
Tidenes don't have that kind of money so they have to attent these issues right away.

##Tasks
Start with the failures shown in a automated test tool.

1. **Go to wave.webaim.org and use their test tool to find errors and failures**
2. Clone or download the code
3. Fix the errors and warnings from wave.webaim in the code
4. Are there other issues with the website that wave doesn't catch? **Inspect the code!**
   - Can you tab-your way through the website?
   - Are the alternative image-texts good and descriptive?
   - Can you find visible text that isn't coded as text?
   - Are there html-elements that could be changed? 
     - Are all buttons actually buttons?
     - Are links coded as links?
     - Are there any divs; can they be something else?


###Styling issues to look for:
1. Are the color contrasts approved?
   1. go to contrast-ratio.com
   2. Pick a background-color from the page and paste the color code into the left field (background)
   3. find the color of the text that is showing on that background and paste into the right field (text color)
2. Is there any content where you need to separate colors to understand the content?
3. Will focus and hovering buttons, links and other interactive elements help indicate if it is clickable?
   - How about hovering on things that does nothing? Any "traps"?
   
   
### if you're super efficient and somehow already fixed everything:
Here are some other fun tools you can play around with:

1. Chrome plugin Lighthouse
2. Plugin ChromeLens
   - Trace tab path
   - test different blindness variations
   - Run accessibility checks
3. Web Developer plugin
   - lets you inactivate styling, images, cookies, js etc
4. Tota11y Plugin
   - Can quickly check color contrasts
   - hover over items to see what a screen reader can read
   