# webscraping
# Imports, definition of functions, ...

if __name__ == "__main__":
    # The code that runs when the program is launched...
    
import sys

if __name__ == "__main__":
    # All your code...
    # Imports if necessary 

if __name__ == "__main__":
    INPUT_FILE = "stipple_throated_antwren.txt"
    # Code to read and print the contents of that file...
    
import sys
import argparse

if __name__ == "__main__":
    parser = argparse.ArgumentParser()
    # ... Set up argparse ...
    args = parser.parse_args(sys.argv[1:])
    # ... Rest of your program starts here ...
 
# ... Imports ...

def extract_wikipedia_contents():
    # ... Docstring ...
    # ... 

if __name__ == "__main__":
    # ... Get command line arguments, read file ...
    article_contents = extract_wikipedia_contents(article_html_source)
    # ... Print article contents ...
    
"""Extract the text of a Wikipedia article from HTML

    Here, it would be useful to describe a bit more about how you've chosen to
    format the text that you're returning, and what exactly you mean by the
    "article text."

    Args:
        html_source (str): HTML source of a Wikipedia article

    Returns:
        str: The text of the Wikipedia article
    """
    
from wikipedia import extract_wikipedia_contents

import wikipedia

article_contents = wikipedia.extract_wikipedia_contents(article_html_source)

import wikipedia as wp

# ...

    article_contents = wp.extract_wikipedia_contents(article_html_source)
    
from wikipedia import *    
    
