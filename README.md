<div dir="rtl">
<h1>NMAP :</h1>

يتم استخدامها عادةً لمراجعة أمان الشبكة والبحث عن الأجهزة المتصلة على نفس الشبكة وتحديد المنافذ المفتوحة وغيرها من الإستخدامات .
* * *
الصيغة العامة لـ Nmap :
- 
```
nmap [Scan Type...] [Options] {target specification}
```

لمعرفة الأجهزة المتصله على نفس الشبكة:

```
nmap -sn target 
```

```
nmap -sP target
``` 


لمعرفة الـ ports المفتوحة والخدمات 

```
nmap -sV target
```


لمعرفة نظام التشغيل :
 
 ```
nmap -O target
```

الـ syn scan 

```
nmap -sS target
``` 
الـ TCP scan 

```
nmap -sT target
``` 
الـ UDP scan 

```
nmap -sU target
``` 
لمعرفة جميع الـ ports المفتوحة:
```
nmap -p- target
``` 
لتحديد port محدد:
```
nmap -p number-port target
```
  
  كل التوفيق
  <br>
  أصالة العصيمي.
  <div>
