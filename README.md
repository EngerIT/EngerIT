import random
print(' Thay đổi vận mệnh')
xx1=random.randint(1,6)
xx2=random.randint(1,6)
xx3=random.randint(1,6)
tong = xx1 + xx2 +xx3
choose=input("(Vui lòng nhập có dấu) Bạn chọn: ")
tien=int(input("Mức cược cảu bạn là: "))
tienthang = tien + (tien/100)*90
if tong <11:
    print('Xỉu',tong)
    a="xỉu"
else :
    print('Tài',tong)
    a="tài"
if choose == a:
    print('Chúc mừng bạn')
    print('Bạn đã thắng', tienthang)
else:
    print('Chúc bạn may mắn lần sau')
