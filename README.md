Sean Yang

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

    Within a Github action that runs whenever code is pushed 

Github action would be best choice as having automated testing occur within every push showcases continuous integration, making it "instantly automatic"


2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   
no, automated testing is unnecessary. Unit testing will display result and is sufficient enough. E2E will test from beginning to end of application, will display unnecessary information. 

3) What is the difference between navigation and snapshot mode?

Navigation mode is for analyzing a page immediately after loading, where one can see the generalized overall performance metric, but is not able to analyze changes in value, from clicking buttons as such. Snapshot mode is to analyze current state of a page, to determine accessibility problems after loading and modifying data points. It is unable to analyze js performance and changes within dom tree. 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. The document does not have a meta description. Include lang attribute to html element.
2. Fix chaining of critical requests 
3. preconnect origins and candidates
4. use efficient cache lifetimes, render blocking requests
5. ensure csp works against xss atttacks, use strong hsts policy