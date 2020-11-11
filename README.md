# JSP-Reverse-and-Web-Shell
A simple reverse and as well a webshell that recognices the OS (Windows/Linux).


This is a 2 way shell, one web shell and a reverse shell. First, it will try to connect to a listener (atacker machine), with the IP and Port specified at the end of the file.
If it cannot connect, an HTML will prompt and you can input commands (sh/cmd) there and it will prompts the output in the HTML.
Note that this last functionality is slow, so the first one (reverse shell) is recommended. Each time the button "send" is clicked, it will try to connect to the reverse shell again (apart from executing the command specified in the HTML form). This is to to keep it simple.
