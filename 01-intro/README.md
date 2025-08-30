https://www.youtube.com/watch?v=ozCpmkbJNJE&list=PL3MmuxUbc_hIB4fSqLy_0AfTjVLpgjV3R&index=3

In the Github page:
1. Code/Create codespace on main to create a codespace
2. open it in VScode
3. in the VScode terminal: 
    $ docker run hello-world
    $ which python
    $ python -V
    $ pip install tdqm, notebook(==7.1.2),openai elasticsearch scikit-learn pandas
    #platform.openai.com to create a secret key
    $ export OPENAI_API_KEY="xyz"
    $ jupyter notebook
          import openai
          from openai import OpenAI
          client = OpenAI()
          import os
          os.environ
          response = client.chat.completions.create(
              model='gpt-5-mini',
              messages =[{"role":"user","content":"what is the weather today in houston,TX?"}]
          )
          response.choices[0].message.content
     $ git status
     $ git add .
     $ git commit -m "home work 1"
     $ git push (use folder and rename to put all files into a organized way before git push)
  4. in the Github page Code/On current brach: Active Codespace --> Stop Codespace and Delete (codespace)
     
     
