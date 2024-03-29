# Hi there :wave:

[[Homepage](https://winum.dev/ "Homepage")] 
[[LinkedIn](https://www.linkedin.com/in/joakim-winum-lien-55359494/ "LinkedIn")] 
[[Repositories](https://github.com/joakimwinum?tab=repositories "Repositories at GitHub")] 
[[Docker Hub](https://hub.docker.com/u/joakimwinum "Docker Hub")]

## Try out some of my public work

Prerequisite: *Container runtime*

- [[2018](# "Year of release: 2018")] 
[[PHP](# "Main programming language: PHP")] 
[[Repository](https://github.com/joakimwinum/php-snake "Source code")] 
[[Package](https://hub.docker.com/r/joakimwinum/php-snake "Container image")] 
[[License](https://github.com/joakimwinum/php-snake/blob/main/LICENSE "License: MIT")] 
[[CLI](# "Run from the command line")] 
[[Games](# "Category: Games")] 
**PHP Snake CLI Game**[^container_runtime_assumption]
  ```console
  docker run -it --rm --name php-snake joakimwinum/php-snake
  ```
- [[2018](# "Year of release: 2018")] 
[[PHP](# "Main programming language: PHP")] 
[[Repository](https://github.com/joakimwinum/php-turingmachine "Source code")] 
[[Package](https://hub.docker.com/r/joakimwinum/php-turingmachine "Container image")] 
[[License](https://github.com/joakimwinum/php-turingmachine/blob/main/LICENSE "License: MIT")] 
[[CLI](# "Run from the command line")] 
[[Emulators](# "Category: Emulators")] 
**PHP Turing Machine**[^container_runtime_assumption]
  ```console
  docker run -it --rm --name php-turingmachine joakimwinum/php-turingmachine
  ```
- [[2019](# "Year of release: 2019")] 
[[Python](# "Main programming language: Python")] 
[[Repository](https://github.com/joakimwinum/py-snake "Source code")] 
[[Package](https://hub.docker.com/r/joakimwinum/py-snake "Container image")] 
[[License](https://github.com/joakimwinum/py-snake/blob/main/LICENSE "License: MIT")] 
[[CLI](# "Run from the command line")] 
[[Games](# "Category: Games")] 
**Py Snake CLI Game**[^container_runtime_assumption]
  ```console
  docker run -it --rm --name py-snake joakimwinum/py-snake
  ```
- [[2019](# "Year of release: 2019")] 
[[JavaScript](# "Main programming language: JavaScript")] 
[[Repository](https://github.com/joakimwinum/js-snake "Source code")] 
[[Package](https://hub.docker.com/r/joakimwinum/js-snake "Container image")] 
[[License](https://github.com/joakimwinum/js-snake/blob/main/LICENSE "License: MIT")] 
[[Browser](http://localhost:8080/ "Run from the browser")] 
[[Games](# "Category: Games")] 
**JS Snake**[^container_runtime_assumption]
  ```console
  docker run --rm --name js-snake -p 8080:80 joakimwinum/js-snake
  ```

[^container_runtime_assumption]: The code block is assuming that you are using [Docker Engine](https://docs.docker.com/engine/install/ "Install Docker Engine")  as your container runtime.
