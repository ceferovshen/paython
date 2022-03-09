Login = 'Rovshan'
Parol = 'z'
loginn = None
Paroll = None
CehdSayi = 0
while Login.title() != loginn and Parol != Paroll:
    CehdSayi += 1
    #continue
    #hemen emeliyyatti bitirir bu veziyyetde CehdSayi hemese 1 olacaq (0'da ola biler ))))
    if CehdSayi > 3:
        print(str(CehdSayi-1) + ' defe sehf etdiniz. Yeni cehd ucun 1 deqiqe gozlemelisiz')
        break
    #break cikli bitirir,novbeti etapa kecir
        
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
    print(str(CehdSayi) + 'Bitti')    
 #Novebti etap   
  
