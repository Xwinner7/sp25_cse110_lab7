# Lab 7 - Unit & E2E Testing
Name: Xiuwen Zhu
## Check Your Understanding
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   - Would fit my automated tests with option 1 which is `within a Github action that runs whenever code is pushed`. This is because testing each push guarantees real time feedback on any malfunctioning features and helps identify the problem before it reach the main branch. Making sure that the code passes through all the tests before merging.
2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   - No
3) What is the difference between navigation and snapshot mode?
   - The difference is that the navigation mode loads the page from the beginning, similar to how a genuine user would. It evaluates the site's usability, how quickly pages load, and when items become visible. This gives a comprehensive view of the user experience over time. On the other hand, snapshot mode quickly examines the page's current state without going through a complete load. It analyzes only the current content display on the screen. While snapshot mode is faster and useful for checking such as accessibility, best practices, and SEO at a glance, navigation mode is better for testing performance and load speed.
4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   - Firstly, it could be improving accessibility by making sure that all interactive components such as buttons are appropriately labeled for screen readers and have enough contrast for users with visual impairments. Secondly, only loading images as the user scrolls down, such could speed up the loading time of the website. Thirdly, could ensure that all resources are loaded over HTTPS and that there are no JavaScript errors or out of date libraries in order to maintain best practices. Hence performance, accessibility, best practices, and SEO would come to an improvement with these adjustments.
