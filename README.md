# Spyder:
This is a tool I made following Ryan John's Python for Hackers Course, https://www.youtube.com/watch?v=0fC1JsN8AsM.
It is used for scrapping (spydering) websites to find all links related to the domain name, excluding unrelated links. It will output a list of the valid links that can then be copied in to a .txt file. With this .txt, you can use the command "cat outputlist.txt | python prober.python". The prober.py tool will search all the links found by spyder.py and return wether or not they are in operation. 

# Prober:
This is a tool I made following Ryan John's Python for Hackers Course, https://www.youtube.com/watch?v=0fC1JsN8AsM.
It is used for probing (prober) websites to check all links related to a valid domain name, excluding unrelated bad pages or pages that are not in operation. It will output a list of the valid links that can then be searched, knowing they are operable sites. The prober.py tool will search all the links found by spyder.py and return wether or not they are in operation. 
