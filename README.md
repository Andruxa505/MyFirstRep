Это поверхностный код:

name = input("Введите ваш никнейм: ")
if True:
	print("[" + name + "] - присоединился.")
	while True:
		msg = input("Введите сообщение: ")
		print("[" + name + "] : " + msg)
