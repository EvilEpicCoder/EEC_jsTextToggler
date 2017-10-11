 ## EEC_jsTextToggler
 ### Simple JavaScript text toggle plug and play script

 #### 1.Project
 * Project created for toggle(unwrap) text in the div
 * Why it created, which problens solved: Created for my portfolio and for programming practice, wrap unwrap text in regular sites.
 * Small story telling : Like to create my small library, so I did this.

 #### 2. What I use in this project
* Frameworks : clean JavaScript and CSS
* Links: [Animated screenshot](https://github.com/EvilEpicCoder/EEC_jsTextToggler/blob/master/screenshot.gif)
* What cool things I found: it is small and it is my!
* What I do not like: It do not change text ,but wrapped text loose some beauty.
* Features: PLUG and PLAY
  * Connect this:
   ```HTML
   <link rel="stylesheet" href="jsTextToggler.css"/>
   <script type="text/javascript" charset="UTF-8" src="EEC_jsTextToggler.js"></script>
   <!-- by default in EEC_jsTextToggler.js function start() is running, for advanced 
   features comment start function -->
   ```
  * Name your div as "info"
  * Init in JavaScript file like:
   ```JavaScript
   var a=new Object(jEEC_info);
   a.start();
   ```
* Advanced Features:
  * You can change `"classSelector":"info"`and `"textLimit":10`
  ```JavaScript
  var a=new Object(jEEC_info);
  a.classSelector='my-div-class';//now will be selected this class instead "info"
  a.textLimit=50;// change from 10 characters to 50 characters
  a.start();
  ```

 #### 3. My thoughts
 * Pros and Cons : Easy connect / shorted text is little ugly.
 * Time consumption: I write this pretty slow and task was plug and play, I did 6 more scripts but they required some rules and little programming, I spend 4 full days.
 * What I learned JavaScript Objects and Object oriented programming.


Version: 0.5b Date: 07.10.2017
