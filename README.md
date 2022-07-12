# Website-blocker-application
A python application that restricts entry into websites during some part of day.
Libraries used in this application are time and datetime for getting the current time of the day and also to give a delay in responding. 
Implemented with the help of Python programming ,HTML, CSS, Javascript.

Motivation
In the present scenario social media, shopping, videos, games...these apps and websites are scientifically engineered to keep you hooked and coming back. The cost to your productivity, ability to focus and general well-being can be staggering.

Features
We first decide a duration in which we want to block the websites. We also decide which websites have to be blocked. Then we check if our current time is in the duration. If it is then we write to the hosts file local machine ip address and the website(domain) name. If it is outside the duration then we erase the file contents.
