# python3-wordlist

#!/usr/bin/python3

import os,sys,time

try:
   while(True):
      if(os.name == 'nt'):
         os.system('cls')
         os.system('mode 150')
         os.system('color b')
      else:
         continue
      print('''
           #############  ##             ##   ###############         ####################   #####################
           #############  ##             ##   ###############   ##    ####################   #########&%##########
           ##             ##             ##   ##           ##  ##     ##                            ##**##
           ##             ##             ##   ##           ## #       ##                            ######
           ##    #######  #################   ##           ###        ####################          ##**##
           ##    #######  #################   ##           ##         ####################          ######
           ##         ##  ##             ##   ##           ##                           ##          ##**##
           ##         ##  ##             ##   ##           ##                           ##          ######
           #############  ##             ##   ###############         ####################          ##**##
           #############  ##             ##   ###############         ####################          ######''')
                                                                                                                        
                                                                                                                                                  
      sec = input('[1].wordlisti oluştur\n[2].çıkış\n:')
      	    
      if (sec == '1'):
         print('vericeginiz ilk rakamın bir gerisinden veriniz')
         a = int(input('wordlisiniz oluşturmak için başlangıç rakamınızı belirliyiniz:'))
         b = int(input('wordlistinizi sonlandormak için rakam belirleyin:'))
         qwerty = input('wordlist\'inizin adını yazınız(isterseniz diziniyle birlikte yazabilirsiniz sonuna .txt kaymazsanız hata alırsınız):')
         ad = input('ad:')
         s = input('soyad:')
         y = input('yaş:')
         d = input('dogum tarihi(arayanokta koymadan yazınız):')
         ba = input('baba ad:')
         bs = input('baba soyad:')
         by = input('baba yaşı:')
         bd = input('baba dogum tarihi(araya noktakoymadan yazınız):')
         aa = input('anne ad:')
         ass = input('anne soyad:')
         ay = input('anne yaş:')
         add = input('anne dogum tarihi(araya noktakoymadan yazınız):')
         ka = input('kardeş ad:')
         ks = input('kardeş soyad:')
         ky = input('kardeş yaş:')
         kd = input('kardeş dogum tarihi(araya noktakoymadan yazınız:')
         sa = input('sevgili ad:')
         ss = input('sevgili soyad:')
         sy = input('sevgiliyaş:')
         sd = input('sevgili dogum tarihi(araya noktakoymadan yazınız):')
         sss = input('sevdigi sarkıcı:')
         sss2 = input('sevdigi kişi:')
         dosya = open(qwerty,'w')
         dosya.close()
         qazxsw = a
         while(True):
            dosya  = open(qwerty,'r+')
            a = int(a) + int(1)
            data = dosya.readlines()
            lst = [data , a]
            q = str(a) + str(ad)
            w = str(a) + str(s)
            e = str(a) + str(y)
            r = str(a) + str(d)
            t = str(a) + str(ba)
            y = str(a) + str(bs)
            u = str(a) + str(by)
            ı = str(a) + str(bd)
            o = str(a) + str(aa)
            p = str(a) + str(ass)
            l = str(a) + str(ay)
            s = str(a) + str(add)
            d = str(a) + str(ka)
            f = str(a) + str(ks)
            g = str(a) + str(ky)
            h = str(a) + str(kd)
            z = str(a) + str(sa)
            x = str(a) + str(ss)
            c = str(a) + str(sy)
            v = str(a) + str(sd) #toplam = 20
            lst = [data,a,q,w,e,r,t,y,u,ı,o,p,l,s,d,f,g,h,z,x,c,v]
            print(lst[1],'\n',lst[2],'\n',lst[3],'\n',lst[4],'\n',lst[5],'\n',lst[6],'\n',lst[7],'\n',lst[8],'\n',lst[9],'\n',lst[10],'\n',lst[11],'\n',lst[12],'\n',lst[13],'\n',lst[14],'\n',lst[15],'\n',lst[16],'\n',lst[17],'\n',lst[18],'\n',lst[19],'\n',lst[20],sep = '')
            print(lst[1],'\n',lst[2],'\n',lst[3],'\n',lst[4],'\n',lst[5],'\n',lst[6],'\n',lst[7],'\n',lst[8],'\n',lst[9],'\n',lst[10],'\n',lst[11],'\n',lst[12],'\n',lst[13],'\n',lst[14],'\n',lst[15],'\n',lst[16],'\n',lst[17],'\n',lst[18],'\n',lst[19],'\n',lst[20],sep = '',file = dosya ,flush = True)
#           qwrtyuıoplsdfghzxcv
            q = str(ad) + str(a)
            w = str(s) + str(a)
            e = str(y) + str(a)
            r = str(d) + str(a)
            t = str(ba) + str(a)
            y = str(bs) + str(a)
            u = str(by) + str(a)
            ı = str(bd) + str(a)
            o = str(aa) + str(a)
            p = str(ass) + str(a)
            l = str(ay) + str(a)
            s = str(add) + str(a)
            d = str(ka) + str(a)
            f = str(ks) + str(a)
            g = str(ky) + str(a)
            h = str(kd) + str(a)
            z = str(sa) + str(a)
            x = str(ss) + str(a)
            c = str(sy) + str(a)
            v = str(sd) + str(a)
            lst = [data,a,q,w,e,r,t,y,u,ı,o,p,z,x,c,v,h]
            print(lst[1],'\n',lst[2],'\n',lst[3],'\n',lst[4],'\n',lst[5],'\n',lst[6],'\n',lst[7],'\n',lst[8],'\n',lst[9],'\n',lst[10],'\n',lst[11],'\n',lst[12],'\n',lst[13],'\n',lst[14],'\n',lst[15],sep = '')
            print(lst[1],'\n',lst[2],'\n',lst[3],'\n',lst[4],'\n',lst[5],'\n',lst[6],'\n',lst[7],'\n',lst[8],'\n',lst[9],'\n',lst[10],'\n',lst[11],'\n',lst[12],'\n',lst[13],'\n',lst[14],'\n',lst[15],sep = '',file = dosya ,flush = True)
            dosya.close()
            int(a)
            print('bitti son olan rakam',a)
            if (a == b):
               sys.exit()
            else:
               continue
      else:
         sys.exit()
               
except KeyboardInterrupt:
    print('\ngörüşürüz')
    sys.exit()

except EOFError:
    print('\ngörüşürüz')
    sys.exit()

except PermissionError:
    print('lütfen dosyanın özelliklerine bakmayınız')
    sys.exit()
