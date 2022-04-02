Google Search
============

Google search from Python.

https://python-googlesearch.readthedocs.io/en/latest/

Usage example
-------------

    # Get the first 20 hits for: "Breaking Code" WordPress blog
    from googlesearch import search
    proxies={'https': 'socks5://127.0.0.1:1080', 'http': 'socks5://127.0.0.1:1080'}
    for url in search('"Breaking Code" WordPress blog', proxies=proxies, stop=20):
        print(url)

Installing
----------

    pip install google
