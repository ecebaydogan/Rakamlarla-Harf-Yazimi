# Rakamlarla-Harf-Yazimi
Python dilinde rakamlara atadığımız değerlerle harf / kelime yazımı.
karakter = open("C:/Users/Admin/Desktop/metin.txt", 'r', encoding='utf-8')
giris = karakter.read()
karakter.close()
yazi =""

for i in giris.split("."):
    match i.upper():
        case "1":
           yazi = yazi + "a"
        case "2":
           yazi = yazi + "b"
        case "3":
           yazi = yazi + "c"
        case "4":
           yazi = yazi + "ç"
        case "5":
           yazi = yazi + "d"
        case "6":
           yazi = yazi + "e"
        case "7":
           yazi = yazi + "f"
        case "8":
           yazi = yazi + "g"
        case "9":
           yazi = yazi + "ğ"
        case "10":
           yazi = yazi + "h"
        case "11":
           yazi = yazi + "ı"
        case "12":
           yazi = yazi + "i"
        case "13":
           yazi = yazi + "j"
        case "14":
           yazi = yazi + "k"
        case "15":
           yazi = yazi + "l"
        case "16":
           yazi = yazi + "m"
        case "17":
           yazi = yazi + "n"
        case "18":
           yazi = yazi + "o"
        case "19":
           yazi = yazi + "ö"
        case "20":
           yazi = yazi + "p"
        case "21":
           yazi = yazi + "r"
        case "22":
           yazi = yazi + "s"
        case "23":
           yazi = yazi + "ş"
        case "24":
           yazi = yazi + "y"
        case "25":
           yazi = yazi + "u"
        case "26":
           yazi = yazi + "ü"
        case "27":
           yazi = yazi + "v"
        case "28":
           yazi = yazi + "y"
        case "29":
           yazi = yazi + "z"
        case "30":
           yazi = yazi + " "
        case "31":
           yazi = yazi + "."
           
cevap = open("C:/Users/Admin/Desktop/sonuç.txt", 'w', encoding='utf-8')
cevap.write(yazi)
