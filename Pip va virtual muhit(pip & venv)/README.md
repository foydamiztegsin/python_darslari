# **Pip va virtual muhitlar yordamida paketlarni o'rnatish** 


# __pip__
> Python paketlarini o'rnatish uchun eng mashhur vosita va Pythonning zamonaviy versiyalari bilan birga.

> U PyPI va boshqa Python paket indekslaridan paketlarni topish, yuklab olish va oʻrnatish uchun muhim asosiy xususiyatlarni taqdim etadi va buyruq qatori interfeysi (CLI) orqali keng koʻlamli ishlab chiqish ish oqimlariga kiritilishi mumkin.

pip - bu Python paket menejeri. U paketlarni o'rnatish va yangilash uchun ishlatiladi. Sizda pipning so'nggi versiyasi o'rnatilganligiga ishonch hosil qilishingiz kerak.

- Windows uchun Python o'rnatuvchilari pipni o'z ichiga oladi. Pip-ning yangilanganligiga ishonch hosil qilishingiz mumkin:
	- py -m pip install --upgrade pip
	- py -m pip --version


# __Pipenv__

> Pipenv - bu Python dunyosiga qadoqlash dunyosining eng yaxshisini olib kelishga qaratilgan loyiha. U Pipfile , pip va virtualenv ni bitta asboblar zanjirida birlashtiradi. U avtomatik import qilishi va xavfsizlik yordamida Pipfile'da CVE'larnirequirements.txt tekshirishi mumkin .

> Pipenv foydalanuvchilarga buyruq satrida muhitlar, bog'liqliklar va import qilingan paketlarni boshqarishda yordam berishni maqsad qilgan. Bundan tashqari, u Windowsda yaxshi ishlaydi (boshqa vositalar ko'pincha kam xizmat qiladi), xesh-qulflangan bog'liqlik spetsifikatsiyalariga muvofiqligini ta'minlash uchun fayllar xeshlarini yaratadi va tekshiradi hamda paketlar va bog'liqliklarni o'chirishni osonlashtiradi.


# __Pipfile__

> Pipfileva uning singlisi pip ning quyi darajadagi fayliga Pipfile.lockyuqori darajadagi dasturga asoslangan alternativ hisoblanadi .requirements.txt



# __virtualenv__
- virtualenv turli loyihalar uchun Python paketlarini boshqarish uchun ishlatiladi. Virtualenv-dan foydalanish tizim vositalarini yoki boshqa loyihalarni buzishi mumkin bo'lgan global Python paketlarini o'rnatishdan qochish imkonini beradi. Virtualenvni pip yordamida o'rnatishingiz mumkin.
	- O'rnatish:
		- py -m pip install --user virtualenv
# __venv__
> Virtual muhit yaratish uchun Python standart kutubxonasidagi paket (Python 3.3 dan boshlab)


# __Virtual muhit yaratish__
> venv (Python 3 uchun) va virtualenv (Python 2 uchun) turli loyihalar uchun alohida paketli o'rnatishlarni boshqarish imkonini beradi. Ular aslida "virtual" izolyatsiyalangan Python o'rnatishni yaratishga va ushbu virtual o'rnatishga paketlarni o'rnatishga imkon beradi. Loyihalarni almashtirganingizda, siz shunchaki yangi virtual muhit yaratishingiz mumkin va boshqa muhitlarda o'rnatilgan paketlarni buzish haqida tashvishlanishingiz shart emas. Python ilovalarini ishlab chiqishda har doim virtual muhitdan foydalanish tavsiya etiladi.

- Virtual muhit yaratish uchun loyihangiz katalogiga o'ting va venv-ni ishga tushiring. Agar siz Python 2 dan foydalanayotgan bo'lsangiz , quyidagi buyruqlar venvbilan almashtiring.virtualenv:
	- py -m venv env
	- Ikkinchi dalil - virtual muhitni yaratish uchun joy. 
	Umuman olganda, siz buni loyihangizda yaratishingiz va uni chaqirishingiz mumkin env.
		venv envpapkada virtual Python o'rnatilishini yaratadi.
	**Eslatma**
	>  Siz o'zingizning virtual muhit katalogingizni versiyalarni boshqarish tizimidan .gitignoreyoki shunga o'xshash usullardan foydalangan holda chiqarib 		tashlashingiz kerak.

# __Virtual muhitni faollashtirish__
- Virtual muhitda paketlarni o'rnatish yoki foydalanishni boshlashdan oldin uni faollashtirishingiz kerak bo'ladi. Virtual muhitni faollashtirish virtual muhitga xos pythonva pipbajariladigan fayllarni qobiqqa joylashtiradi PATH.
	- .\env\Scripts\activate
	- Virtual muhitingiz faollashtirilgan ekan, pip o'sha maxsus muhitga paketlarni o'rnatadi va siz Python ilovangizda paketlarni import qilishingiz va 				ishlatishingiz mumkin bo'ladi.







- [Manba](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)
- [Manba](https://packaging.python.org/en/latest/key_projects/#pip)



















