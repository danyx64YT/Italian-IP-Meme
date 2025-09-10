This repository is a translation and modification of another repository (I don't remember the name and don't want to look it up).
With this repository, you can get someone's IP address in a (fun) way.

- Installation Steps -
Download Node.JS from their website "https://nodejs.org/en/" and install it.
Download this repository and extract it wherever you want.
Open a terminal in the folder containing the repository files.
In the terminal, enter "npm install http-server".
Perfect, if it didn't give any errors (which it probably won't), just type "http-server" in the same terminal.
It should give you a list of mostly local IPs from which to access the site.

The most likely ones are:
- 127.0.0.1:8080
- 127.0.0.1:8081

The port varies if one of the two is already in use; it will tell you so in the terminal.
The IPs accessing the site will appear in the terminal.
This site is only accessible to you on your local network unless you follow the steps below.

If you want to host it online, there are several methods:
- NGINX: You must have a PC or server at home that is always on and forward the port (not very secure), or use
a free public tunneling service like PlayIT. Although it's designed for games, it also works for this or other services of your choice.
- GitHub CodeSpaces.
- Other Free or Paid Hosting Services.

Since this repository is a website, you can deploy it almost anywhere with some effort, even on your phone.