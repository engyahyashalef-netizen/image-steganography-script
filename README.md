# image-steganography-script
A simple Python script for hiding secret text data inside image files seamlessly.
# ==========================================
# المطور: يحيى مجاهد صالح شالف
# Developer: Yahya Mujahed Saleh Shalef
# المشروع: سكريبت إخفاء النص في الصورة
# ==========================================

img = open("2.jpg", "rb")
img_read = img.read()
print(img_read)

file = open("2.jpg", "a")
file.write("...............>>>>> name : yahya shalef <<<<<...........")
file.close()
print("encoded")
