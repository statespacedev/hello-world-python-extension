![intro](./docs/intro.png)

this micro project is about get-it-going 'python extension in the debugger' - clion and pybind11 are used - links to begin further explorations are - 

- https://www.jetbrains.com/help/clion/debugging-python-extensions.html 
- https://pybind11.readthedocs.io/en/stable/compiling.html#building-with-cmake 

yet again, as in years past, cmake ends up being the way - rather than setuptools, pyproject.toml, other 'web-dev' stuff - in particular - 

- pyproject.toml is a major show-stopper - it's causing the build to happen in a 'hidden virtual environment' - end result - debugger can't see breakpoints set in the .cpp file. probably fixable - why waste time fixing something like this?
- without cmake, it's hard to insure the build is in debug mode - with cmake, it's simple.

in a nutshell - old school caveman c style - not 'web-dev' style.
