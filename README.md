# pw2

This is an android app that I created to help manage my passwords. The way that I generate passwords for sites is to take the domain of the site and concat that with a pin that only I know. I then perform a series of computations (which are obviously omitted from this repo) on this concatenated string the result of which is my password. When I need to login to a site, I get the password the same way that I created it. 

The benefits of this approach are: 
1. My password for no two sites is the same. So if my password from one site gets leaked, I don't need to worry about other sites being comprimised
2. I only have to remember my pin
3. Even if someone somehow gets my pin, they wouldn't know the computational steps to go from pin to password. And vice versa, if someone where to figure out the computational steps I use, it would still require my pin to generate any passwords
