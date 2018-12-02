## Debugging Process

1. Run your program
2. Are there any other error messages?
  * Yes? READ THEM, then go to step3
  * No? Put in a 'p' or 'console.log' at the beginning of your code
    - Re-run your code
    - Do you see your message?
      * Yes? Go to step3
      * No? Program is most likely crashing while loading - dependency/build related issue?
3. Get Visibility
  * Read the stack trace of the error message
  * See where the error occurred, identify the exact line number
  * USE YOUR TOOLS
    - Throw in 'p' statements or 'console.log'
    - Use 'binding.pry' to play around in the console with your code
      * Get your code to do what you expect and it should flag where unexpected results are returned
4. Google the error!
  * 99.999% of the time, someone else has had this problem! StackOverflow can be hugely valuable
5. Take a break and go back to it
  * A fresh pair of eyes and clean head can often be the best debugging tool
5. Pair program on the bug
  * If you have exhausted all your ideas/options and find yourself spiralling, ask someone to pair with you on it!
    - Show them the bug in the code
    - Explain everything you've tried to do to solve it
    - Sometimes just talking through the problem and explaining it out loud can help you solve it
      * Rubber ducks are also useful for this if you don't have a pair partner!
