TEST: 
Tried to check that the index.html is working. Problem with secret key when only in env.py
    - Had forgot to add: if os.path.isfile("env.py"):
    import env to settings. Fixed problem.

