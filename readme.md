![intro](./docs/intro.png)

micro project around get-it-going 'python extension in the debugger' - we've been doing this for many years now, good to keep the instincts warm - also good to periodically come in with 'beginners mind' to see what the current state of the art is - clion and pybind11 are used here - links to begin further explorations are - 

- https://www.jetbrains.com/help/clion/debugging-python-extensions.html 
- https://pybind11.readthedocs.io/en/stable/compiling.html#building-with-cmake 

yet again, as in years past, cmake ends up being the way - rather than setuptools, pyproject.toml, other 'web-dev' stuff - in particular - 

- pyproject.toml / setuptools are a major show-stopper - the build's happening in some kind of 'hidden virtual environment' - end result - debugger can't see breakpoints set in the .cpp file. probably fixable - why waste time fixing something like this?
- without cmake, it's hard to know the build is in debug mode - with cmake, it's simple.

in a nutshell - old school caveman style - not 'web-dev' style.
