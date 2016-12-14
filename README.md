
# FindPythonSphinx

CMake module for Sphinx HTML docs  

Include to try to find Sphinx, and if successful:
  - set Sphinx_FOUND 
  - add a target ${PROJECT_NAME}_doc with the HTML docs
  - if there is a conf.py.in it will configure and use it
  - otherwise it will use conf.py

The following can be customized, use ccmake for the descriptions
- SPHINX_THEME
- SPHINX_THEME_DIR
- SPHINX_BUILD_DIR 
- SPHINX_CACHE_DIR 
- SPHINX_HTML_DIR   

