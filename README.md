# Maptac Chess

This is a JavaScript chess game I wrote with [Jacob Taylor](http://stanford.edu/~jacobt) in high school. You can either play a game against somebody on the same computer or against a very simple AI.

The AI player was originally written in Common Lisp and then ported to JavaScript. This should explain the slightly odd feel to the JavaScript code in the AI. Additionally, JavaScript's performance--at least back when this was originally written--was significantly worse than Common Lisp's, so the JS version only looks 3 moves ahead by default where the original could do up to 5 comfortably. If you have a fast browser, you can control the depth using the `AI_DIFFICULTY` variable. Even several years ago looking 4 moves ahead was reasonable, so recent performance improvements may have even made 5 plausible.

The UI was implemented with prototype.js and script.aculo.us. Remember prototype? I wrote the initial version of this before jQuery had a virtual stranglehold on the market. That said, I actually rather like prototype--not as much as jQuery, admittedly. And I *do* like scrip.aculo.us more than anything equivalent I've tried for jQuery.