# 50-masala
#  1- masala
 # ball = float(input("Ballni kiriting: "))

# if ball < 0 or ball > 100:
#     print("Xato:Ball o dan 100 gacha bolishi kerak.")

#     if 90 < ball < 100:
#         print("A")

#     if 80 < ball < 89:
#         print("B")

#     if 70 < ball < 79:
#             print("C")

#     if 60 < ball < 69:
#             print("D")

#     if 0 < ball < 59:
#         print("F")

# 2 - masala
# yosh = float(input("Yoshni kiriting: "))
# daromat = float(input("Daromatni kiriting: "))
# if yosh < 18:
#     print("Soliq 0%")

#     elif  yosh <= 60 and daromad > 5000:
#         print("Soliq 20%")

#     else:
#             print("Soliq 10%")
#         else:

#             print("Soliq 5%")   
# 3 - masala 
# kun = float(input("Hafta kunini kiriting(1 - 7): "))
# soat = float(input("Soatni kiriting(0 - 23): "))


# if kun < 1 or kun > 7 or soat < 0 or soat > 23:
#     print("Xato:Kun 1-7, soat 0-23 oraligida bolishi kerak")
# else:

#     if kun == 6 or kun == 7:
#         print("Dam olish kuni")  
#     else:

#         if 9 <= soat <= 17:
#             print("Ish vaqti")  
#         else:
#             print("Ish vaqtidan tashqari")       
# 4 - masala
# try:
#     harorat = float(input("Haroratni kiriting: "))
#     yomgir_input = input("Yomg'ir yogyaptimi(True/False): ")
#     exit()

#     if yomgir_input == 'True':
#         yomgir = True
#     elif yomgir_input == 'False':
#         yomgir = False
#     else:
#         print("Xato:Yomgir qiymati TRUE yoki FALSE bolishi k-k")
       

#     if harorat < -50 or harorat > 60:
#         print("Xato harorat -50 dan 60 gacha bolishi k-k")    
#     else:
#         if harorat <= 0:
#             print("Qor yogishi mumkin") 
#         elif  harorat <= 20:
#             if yomgir:
#                 print("Yomgirli sovuq")
#             else:
#                 print("Sovuq,lekin quruq")    
#         else:
#                 print("Sovuq")  
# 5 - masala:
# masofa = float(input("Masofani kiriting(km): "))
# vaqt = float(input("Vaqtni kiriting: "))
 
# if masofa < 0 or vaqt < 0:
#     print("Xato:Masofa va vaqt manfiy bolmasligi k-k")
# else:
#     if masofa < 5:
#         print("Piyoda boring!")   
#     elif masofa <= 50:
#         if vaqt > 1:
#             print("Avtobus")  
#         else:
#             print("Velosiped")       
#     else:
#         print("Samolyot")
# 6 - masala
# yosh = int(input("Yoshingizni kiriting: "))
# daromad = int(input("Daromadni kiriting: "))
# k_summasi = int(input("Kredit summasini kiriting: "))

# if yosh < 18 or yosh > 100 or daromad < 0 or k_summasi <= 0:
#     print("Xato:Yosh 18 - 100 oraligida, daromad va kredit summasi musbat bolishi k-k")
# else:
#     if yosh < 21:
#         print("Kredit berilmaydi!") 
#     elif yosh <= 60:
#         if daromad > k_summasi * 0.2:
#             print("Kredit tasdiqlandi!")
#         else:
#             print("kredit rad etildi!")   
#     else:
#         print("Kredit faqat maxsus shartlarda!")        
# 8 - masala
#  baho = float(input("Bahoni kiriting: "))
# daromad = float(input("Daromadni kiriting: "))

# if baho < 0 or baho > 5.0 or daromad < 0:
#     print("Xato: Baho 0 - 5.0 oralig'ida, daromad musbat bo'lishi kerak")
# else:
#     if baho < 3.0:
#         print("Stipendiya yo'q")
#     elif baho < 4.0:
#         if daromad < 1000:
#             print("Oddiy stipendiya")
#         else:
#             print("Stipendiya yo'q")
#     else:  # ya'ni baho >= 4.0
#         if daromad < 2000:
#             print("Yuqori stipendiya")
#         else:
#             print("Stipendiya yo'q")     
# 9 - masala 
# daqiqa = float(input("Daqiqani kiriting: "))
# internet = float(input("Internet miqdorini kiriting: "))

# if daqiqa < 0 or internet < 0:
#     print("Xato: Daqiqalar va internet manfiy bo'lishi kerak emas.")
# else:
#     if daqiqa < 100:
#         print("Mini tarif")
#     elif daqiqa <= 500:
#         if internet > 5:
#             print("Standart tarif")
#         else:
#             print("Ekonom tarif")
#     else:
#         print("Premium tarif")
# 10 - masala
# harorat = float(input("Haroratni kiriting: "))
# shamol = float(input("Shamol tezligini kiriting: "))
# if harorat < -50 or harorat > 50 or shamol < 0:
#     print("Xatolik.Harorat -50 dan 50 gacha , shamol manfiy emas. ")

# else:
#     if harorat < 10 and shamol > 10:
#         print("Uyda qoling!")   
#     elif     harorat <= 25:
#         if shamol < 5:
#             print("Sayr qiling!")
#         else:
#             print("Ehtiyot boling!")    
#     else:
#         print("Suv iching")     
# 11 - masala
# soat = float(input("Ish soatlarini kiriting: "))   
# tajriba = float(input("Tajribani kiriting: "))
# if soat < 0 or  tajriba < 0:
#     print("Xato:Soat va tajriba manfiy bolmasligi kerak!") 


# else:
#     if tajriba < 1:
#         ish_haq = soat * 10
#     elif tajriba <= 5:
#         if soat > 40:
#             ish_haq = soat * 15
#         else:
#             ish_haq = soat * 12
#     else:
#         ish_haq = soat * 20
#     print("Umumiy ish vaqti: ${Ish haq}")       
# 12 - masala    
# 1. Oy raqami va haroratni kiritishni so'raymiz
# oy = int(input("Oy raqamini kiriting (1-12): "))
# harorat = float(input("Haroratni kiriting (–50 dan 50 gacha): "))

# # 2. Kiritilgan qiymatlar to‘g‘riligini tekshiramiz
# if oy < 1 or oy > 12 or harorat < -50 or harorat > 50:
#     print("Xato: Oy 1-12, harorat –50°C dan 50°C gacha bo'lishi kerak.")
# else:
#     # 3. Mavsum va haroratni baholaymiz
#     if oy == 12 or oy == 1 or oy == 2:
#         print("Qish")
#     elif 3 <= oy <= 5:
#         if harorat > 15:
#             print("Iliq bahor")
#         else:
#             print("Sovuq bahor")
#     elif 6 <= oy <= 8:
#         print("Yoz")
#     else:
#         print("Kuz")
# # 13 - masala  
# try:
#     summa = float(input("Xarid summasini kiriting: "))   
#     chegirma = (input("Doimiy mijozmisiz(Ha/Yoq): ")).strip().lower()
                
#     if chegirma in ['ha', 'true', 't' '1']:
#     chegirma = True           
#    elif chegirma in ['yoq', 'y', 'false', '0']
#     chegirma = False
#    else:
#        print("Xato:Doimiy mijoz qiymati faqat 'ha' yoki 'yoq' bolishi kerak ")
#        exit()
#    if summa <= 0:
#        print("Xato:Musbat bolishi kk")
#    else:    
       
#        if summa < 100:
#            chegirma = 0
#        elif summa <= 500:
#            if chegirma:
#             chegirma = 10
#            else:
#                chegirma = 5
#            else: 
#              chegirma = 15      
#            print(f"Chegirma: {chegirma}%")
# except ValueError:
#     print("Xato:Iltimos, to'g'ri raqam kirting. ") 
# 14 - masala
# tezlik = float(input("Tezlikni kiriting:(MB/S) "))   
# hajm = float(input("Hajmni kiriting:(MB) "))   
# if tezlik <= 0 or  hajm <= 0:
#     print("Xato:Tezlik va hajm musbat bolishi kerak!")


#     if tezlik < 10:
#         print("Yuklash,sekin")
#     elif tezlik <= 50:
#         if hajm > 1000:
#             print("Ortacha yuklash")
#         else:
#             print("Tez yuklash")    
#     else:
#         print("Juda tez yuklash")   
# 15 - masala 


