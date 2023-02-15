# Password-Generator....


This code made for generated unlimited password. You can use it😊
note:For better view you can use Jupyter Notebook.😊


    import random
    import string

    print("="*47 ,"Welcome to Password Generator", "="*47 )
    text = input("please give a text:-  ")
    name = input("please give another text:-  ")
    while True:
        text_pass = random.choice(text)
        name_pass = random.choice(name)
        sp_pass = random.choice(string.punctuation)
        num_pass = random.choice(string.digits)
        num_pass1 = random.choice(string.digits)
        num_pass2 = random.choice(string.digits)
        password = text_pass + sp_pass + name_pass + "@" + num_pass + num_pass1 + num_pass2
        print(password)
        
        
If you want to lean more things then please join:- https://www.facebook.com/problemsolvewithridoy
