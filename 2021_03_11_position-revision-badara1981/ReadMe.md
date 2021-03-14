# Positioning Practice!

**Instructions**: 

1. Load the HTML document without making any changes. Make sure it looks the same as in the image "static_1.png".


2. STATIC POSITIONING
        - Target the element with id "tochange" in styles.css.
        - Give it a position of "static".
        - Reload the HTML page and confirm that nothing has changed. This is because all elements have a DEFAULT positioning of "static", even if we don't specify this. The only way an element won't have static positioning is if we CHOOSE to change its position using CSS. We will now see some examples of how to do this.


3. RELATIVE POSITIONING
        - Give the "tochange" element a position of "relative".
        - Using what you have learned today, try to move the "tochange" element using left/right/top/bottom so the page looks the same as:

                (a) relative_1.png
                (b) relative_2.png
                (c) relative_3.png
                (d) relative_4.png

        - As you do this, try to keep in mind how your changes relate to the "default" placement of the element. E.g. If you give it some "top", where was its starting position before the "top" was applied? Make sure you understand this - if it is not clear, we will discuss this after you have finished the exercise. :-)


4. FIXED POSITIONING
        - Now give the "tochange" element a position of "fixed".
        - Using what you have learned today, try to move the "tochange" element using left/right/top/bottom so the page looks the same as:

                (a) fixed_1.png
                (b) fixed_2.png
                (c) fixed_3.png
                (d) fixed_4.png

        - REMEMBER: "fixed" means that your element will stay in the same place on the page, even if you scroll up and down the page!

        - As you do this, try to keep in mind how your changes relate to the "default" placement of the element. E.g. If you give it some "top", where was its starting position before the "top" was applied? Make sure you understand this - if it is not clear, we will discuss this after you have finished the exercise. :-)


5. ABSOLUTE POSITIONING
        - Now give the "tochange" element a position of "absolute".
        - Using what you have learned today, try to move the "tochange" element using left/right/top/bottom so the page looks the same as:

                (a) absolute_1.png

        - Now, give the PARENT div a position of "relative", and do nothing to the "tochange" element. Reload the page.

                - Does the page now look like: 
                
                        (b) absolute_2.png?
                
                - If so, what do you think has changed? Remember: we only made one change, to our PARENT element...

        - Based on what you just did, try to move the "tochange" element *USING ONLY ONE* of "top", "bottom", "left" or "right" so the page looks the same as:

                (c) absolute_3.png
                (d) absolute_4.png


6. STICKY POSITIONING
        - Create a new HTML page in the same folder as the current exercise.
        - Open the following link in your web browser: 
        
                https://mdn.github.io/learning-area/css/css-layout/positioning/7_sticky-positioning.html

        - Try to recreate this page by using "sticky" positioning on some elements.
        - If you have time, also try to add some different "top", "bottom", "left" or "right" and see how the effect changes...