Dark Google Search
==================

Entirely based on the original project From @marito. All credit goes to him!

Google search from Python.

https://python-googlesearch.readthedocs.io/en/latest/

Usage example
-------------

    # Get the first 20 hits for: "Breaking Code" WordPress blog
    from googlesearch import search
    
    # Do you like AWS? :)
    for url in search('"Breaking Code" WordPress blog', search_url='custom_search_url', stop=20):
        print(url)

Installing
----------

    git clone https://github.com/bransh/darkgooglesearch/
    python3 setup.py install


