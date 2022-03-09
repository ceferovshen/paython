While 

Login = 'Rovshan'
Parol = 'z'
loginn = None
Paroll = None
while Login.title() != loginn and Parol != Paroll:
    loginn = input("Logini qeyd edin: ")
    Paroll = input("Sifreni qeyd edin: ")
    if Login.title() != loginn.title() and Parol == Paroll:
        print("    Logini sehf yigmisiz")
    elif Login.title() == loginn.title() and Parol != Paroll:
        print("    Sifreni sehf yigmisiz")
    elif  Login.title() == loginn.title() and Parol == Paroll:
        print('    Admin panele xos geldin')
    else:
        print("    Login ve sifre yanlisdir")
    
