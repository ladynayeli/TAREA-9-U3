# TAREA-9-U3

1.-Objetivo

1.1 Objetivo general

Analizar a detalle las características que conforman los circuitos en RLC y resonancia tanto en serie como en paralelo y también conocer los filtros pasivos mediante el uso de información de libros, páginas web y videos.

1.2 Objetivos Específicos

• Desarrollar mapas conceptuales, que permitan un mejor entendimiento y comprensión sobre la impedancia de circuitos, análisis de circuitos, los diferentes filtros pasivos y asi poder desarrollar los ejercicios propuestos.

• Distinguir de forma clara las fórmulas, ya que permitirán resolver ejercicios de manera ordenada y precisa.

• Analizar las definiciones de los temas planteados, para obtener resultados satisfactorios en la resolución de ejercicios

2.-Marco Teórico

![Blue Yellow Geometric Shape Study Tips Graph](https://user-images.githubusercontent.com/105687213/187324074-a6dd34e4-8692-4dd2-a356-dbc315fb5626.jpg)

![Blue Yellow Geometric Shape Study Tips Graph](https://user-images.githubusercontent.com/105687213/187324063-bdea9d6a-180d-47ba-8497-bf3b68b4aeff.png)

3.-Resolución de ejercicios

Impedancia de circuitos RLC en serie

2.Determine la impedancia en la figura 17-59 y exprésela en forma polar.

 ![image](https://user-images.githubusercontent.com/105687213/187324886-422a8c17-79a4-43ee-abea-0a67dfca6041.png)

X_tot=|X_l-X_cl |

X_tot=|80Ω-35Ω|

X_tot=45 Ω

Z=√(R^2+X^2 )<〖tan〗^(-1) (X_tot/R)

Z=√(〖(47)〗^2+〖(45)〗^2 )<〖tan〗^(-1) (45/47)

Z=65.07<43.75°

4.Para el circuito de la figura 17-59, determine la reactancia neta que hará que la magnitud de la impedancia sea igual a 100 Ω.

Z=√(R^2+〖(XL-XC)〗^2 ) =100Ω

√(47^2+〖(X)〗^2 ) =100Ω

〖(47Ω)〗^2+ 〖(X)〗^2=〖(100Ω)〗^2

X^2=〖(100)〗^2-〖(47)〗^2 

X=88.27 Ω

Análisis de circuitos RLC en serie

6.Trace el diagrama fasorial de voltaje para el circuito de la figura 17-59.
Z=65.07<43.75°

I=(4<0°)/(65.07<43.75°)=0.061<43.75° ΩA

VR=(0.061<43.75° Ω)(47<0° Ω) = 2.86<43.75° ΩV

VL=(0.061<-43.75° Ω)(80<90° Ω)=4.88<133.75° ΩV

VC=(0.061<-43.75° Ω)(35<-90° Ω)= 2.14<-46.25° ΩV

![image](https://user-images.githubusercontent.com/105687213/187325035-af6e8906-ad9b-40a9-a24f-30db29821714.png)

Resonancia en serie

10.En la figura 17-61, determine XL, XC, Z e I a la frecuencia resonante

![image](https://user-images.githubusercontent.com/105687213/187325087-6593fbf5-168e-4ffb-bda0-bcb13af72078.png)
 
fr=1/(2π√LC) =1/(2π√((1mH)(45pF)))=750 kHz

I=Vs/R=12/22 =0.55A

XL= 2 πfL=2π(750)(1mH)=4.71 kΩ

XC=1/2πfC=1/(2π(750)(47pF))=4.52 kΩ

Xtot=|4.71 kΩ -4.52 kΩ |=0.019 kΩ

Z=√(〖(22)〗^2+〖(0.19)〗^2 )<〖tan〗^(-1) (0.19/22)

Z=22<0.49°

12.Para el circuito RLC de la figura 17-62, determine la frecuencia resonante.

![image](https://user-images.githubusercontent.com/105687213/187325122-1ad27ea2-b374-4645-a50a-161e9eddf647.png)

fr=1/(2π√LC)= 1/(2π√((0.008mH)(0.015μF)))= 459 kHz

14.En la figura 17-62, determine el ángulo de fase entre el voltaje aplicado y la corriente a las frecuencias críticas. ¿Cuál es el ángulo de fase en condición de resonancia?

I=Vs/R=7.07/10 =7.07mA

XL= 2 πfL=2π(0.008mH)(459 kHz)=23.07Ω

〖θ=tan〗^(-1) (X/R)=〖tan〗^(-1) (23.07/10)=66.57°

Impedancia de circuitos RLC en paralelo

16.Exprese en forma polar la impedancia del circuito de la figura 17-63.

![image](https://user-images.githubusercontent.com/105687213/187325183-ac2df62e-83b5-43b8-8790-a561b5c8cb83.png)
 
Z= 1/(1/(R< 0°)+ 1/(XL< 90°)+1/(XC< -90°)) =  1/(1/(100< 0°)+ 1/(1.13< 90°)+1/(605< -90°))  
= 1/(10 mS+j88mS+j1.65 mS) = 1/(10mS-j86.35mS)

=1/(√(〖(10)〗^2+〖(86.38)〗^2 )<〖tan〗^(-1) (86.35/10)) = 11.5 < -83.39°

18.¿A qué frecuencia el circuito de la figura 17-63 cambia su característica reactiva (de inductiva a capacitiva o viceversa)?

G= 1/(R< 0°) =  1/(100< 0°)  = 10 < 0° kS

BC= 1/(XC< -90°) =  1/(6056<-90°)  = 1.65x10^(-4) <40° kS

BL= 1/(XL< 90°) =  1/(1.13<90°)  = 880 <-90° kS

Análisis de circuitos RLC en paralelo

20.Determine la impedancia total del circuito de la figura 17-63 a 50 kHz.
 
 ![image](https://user-images.githubusercontent.com/105687213/187328902-7e6239f9-4da6-41a1-abe2-7bb694bb762c.png)

1/Z=1/(R∠0°)+1/(X_L∠90°)+1/(X_C∠-90°)

1/Z=1/(100∠0°Ω)+1/(0.02∠90°Ω)+1/(2.2*10^(-8)∠-90°Ω)

1/Z=10∠0°mS+50000∠-90°mS+4.54*10^10∠90°mS

Transformar a rectangular:

1/Z=10mS-50000j mS+4.54*10^10 j mS

1/Z=10mS+4.5*10^10 j mS

Transformar a rectangular:

10mS+4.5*10^10 j mS

C=√((10)^2+(4.5*10^10 )^2 )=4.5*10^10

θ=〖tan〗^(-1)⁡〖((4.5*10^10)/10)=89.99°〗

=4.5*10^10∠89.99°mS

Impedancia total 

Z=1/(4.5*10^10∠89.99°mS)=2.2*10^(-8)∠0°Ω

Resonancia en paralelo

24.¿Cuánta corriente se extrae de la fuente de la figura 17-64 en condición de resonancia? ¿Cuáles son las corrientes inductiva y capacitiva en la frecuencia resonante?

 ![image](https://user-images.githubusercontent.com/105687213/187329891-91c420b6-dbe2-4f50-bed1-580382d42a1b.png)

 ![image](https://user-images.githubusercontent.com/105687213/187329915-1be4c60a-9d96-4d9e-8a97-ca955946d037.png)

ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO

26.Encuentre la impedancia total para cada circuito de la figura 17-65
 
 ![image](https://user-images.githubusercontent.com/105687213/187329926-5d1ce409-d68d-4e33-b95a-735e05dcf7a6.png)

Calcular la impedancia en serie de R y XL:

Z_1=R_1+jX_L=220Ω+j100Ω

Z_1=√(〖R_1〗^2+〖X_L〗^2 )∠〖tan〗^(-1)⁡(X_L/R_1 )

Z_1=√((220)^2+(100)^2 )∠〖tan〗^(-1)⁡(100/220)=241.7∠24.44°Ω

Impedancia de la combinación en paralelo de R1 y Xc, en forma polar:

Z_2=((R_1 X_C)/√(〖R_1〗^2+〖X_C〗^2 ))∠-〖tan〗^(-1)⁡(R_1/X_C )

Z_2=[(220Ω)(150Ω)/√((220)^2+(150)^2 )]∠-〖tan〗^(-1)⁡(220/150)=124∠-55.7°Ω

Z_2=Z_2 cosθ+jZ_2 sinθ

Z_2=124Ω cos⁡〖(-55.7°)+j124Ω sin⁡〖(-55.7°)=70Ω-j102.4Ω〗 〗

Impedancia total es:

Z_tot=Z_1+Z_2=(220Ω+j100Ω)+(70Ω-j102.4Ω)=290Ω-j2.4Ω

Forma polar 

Z_tot=√((290)^2+(-2.4)^2 )∠〖tan〗^(-1)⁡((-2.4)/290)=290∠-0.47°Ω

28.Determine el voltaje entre las terminales de cada elemento mostrado en la figura 17-66, y expréselo en forma polar.

 ![image](https://user-images.githubusercontent.com/105687213/187330078-a93ca03c-5475-405a-9f69-c28b2e465eeb.png)

X_C=1/2ᴨfC=1/2ᴨ(2kHz)(0.0047µF) =16.93kΩ

X_L=2ᴨfL=2ᴨ(2kHz)(1500mH)=18.84kΩ

Impedancia en serie de R1 y XL:

Z_1=R_1+jX_L=33000Ω+j18840Ω

Forma polar 

Z_1=√(〖R_1〗^2+〖X_L〗^2 )∠〖tan〗^(-1)⁡(X_L/R_1 )

Z_1=√((33000)^2+(18840)^2 )∠〖tan〗^(-1)⁡(18840/33000)=37999.2 ∠ 29.7°Ω

Z_2=((R_2 X_C)/√(〖R_2〗^2+〖X_C〗^2 ))∠-〖tan〗^(-1)⁡(R_2/X_C )

Z_2=[(22000Ω)(16930Ω)/√((22000)^2+(16930)^2 )]∠-〖tan〗^(-1)⁡(22000/16930)=13417∠-52.4°Ω

Z_2=Z_2 cosθ+jZ_2 sinθ

Z_2=13417Ω cos⁡〖(-52.4°)+j13417Ω sin⁡〖(-52.4°)=8186.3Ω-j10630Ω〗 〗

Impedancia total 

Z_tot=Z_1+Z_2=(33000Ω+j18840Ω)+(8186.3Ω-j10630Ω)=41186Ω+j8210Ω

Z_tot=√((41186)^2+(8210)^2 )∠〖tan〗^(-1)⁡(8210/41186)=41996∠11.27°Ω

V_C=(Z_2/Z_tot ) V_S=((13417∠-52.4°Ω)/(41996∠11.27°Ω))*12∠0°V=(0.32∠-63.7°)(12∠0°V)

V_C=3.84∠-63.7° V

V_L=(Z_1/Z_tot ) V_S=((37999.2 ∠ 29.7°Ω)/(41996∠11.27°Ω))*12∠0°V=(2.53∠18.43°)(12∠0°V)

V_L=30.4 ∠18.43° V

30.¿Cuál es la corriente a través de R2 en la figura 17-67?
 
 ![image](https://user-images.githubusercontent.com/105687213/187330220-c5615601-ab42-4fba-8de0-8d2644800362.png)

X_C=1/2ᴨfC=1/2ᴨ(0.06kHz)(47µF) =0.056kΩ

X_L=2ᴨfL=2ᴨ(0.06kHz)(390mH)=147kΩ

Z_1=R_2+jX_C=100Ω+j56Ω

Z_1=√(〖R_2〗^2+〖X_C〗^2 )∠〖tan〗^(-1)⁡(X_C/R_2 )

Z_1=√((100)^2+(56)^2 )∠〖tan〗^(-1)⁡(56/100)=114.6 ∠ 29.2°Ω

Z_2=((R_1 X_L)/√(〖R_1〗^2+〖X_L〗^2 ))∠-〖tan〗^(-1)⁡(R_1/X_L )

Z_2=[(100Ω)(147000Ω)/√((100)^2+(147000)^2 )]∠-〖tan〗^(-1)⁡(100/147000)=100∠-0.04°Ω

Z_2=Z_2 cosθ+jZ_2 sinθ

Z_2=100Ω cos⁡〖(-0.04°)+j100Ω sin⁡〖(-0.04°)=100Ω-j0.07Ω〗 〗

Z_tot=Z_1+Z_2=(100Ω+j56Ω)+(100Ω-j0.07Ω)=200Ω+j55.93Ω

Z_tot=√((200)^2+(55.93)^2 )∠〖tan〗^(-1)⁡((55.93)/200)=207.6∠15.6°Ω

I_2=V/Z_tot =(115∠0° V)/(207.6∠15.6°Ω)=0.55∠-15.6° A

I_R2=(R_T/R_2 ) I_2=(50Ω/100Ω)(0.55A)=0.27 A

32.Determine la resistencia y la reactancia totales en la figura 17-68.
 
 ![image](https://user-images.githubusercontent.com/105687213/187330305-e36ef63c-10d4-48cc-bd2a-5d63e1edb0f2.png)
 
 ![image](https://user-images.githubusercontent.com/105687213/187330315-90104f95-ec2f-4c0c-9e0b-df0c69b7c866.png)


-----

12.La frecuencia crítica de un filtro pasaaltas es de 50 Hz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

fc=50Hz

a) 1Hz

-Frecuencia rechazada debido a que es menor que 50 Hz.

b) 20Hz

-Frecuencia rechazada debido a que es menor que 50 Hz.

c) 50Hz

-Frecuencia Crítica.

d) 60Hz

-Permite pasar esta frecuencia ya que es mayor a 50 Hz.

e) 30kHz

-Permite pasar esta frecuencia ya que es mayor a 50 Hz.

14. ¿Cuál es fc para cada filtro de la figura 18-41? Determine el voltaje de salida a fc en cada caso (Vent =10 V).
 
a)
![image](https://user-images.githubusercontent.com/105687213/187330769-ad143d90-3f4b-4418-825b-d48b0b1ee8b9.png)

fc=1/2πRC=1/(2π(100Ω)(10µf))=159.15 Hz

b)
![image](https://user-images.githubusercontent.com/105687213/187330807-451c89c4-c988-496d-8143-c0ffb3132d29.png)

fc=1/2πRC=1/(2π(47Ω)(4.7µf))=338.62 Hz

c)
![image](https://user-images.githubusercontent.com/105687213/187330833-04c7fef0-ee54-456e-9314-4e131e4b9b42.png)

fc=1/2π(L/R) =1/(2π(5mH)/(330Ω))=10.50 kHz

d)
![image](https://user-images.githubusercontent.com/105687213/187330862-9922c8d0-acf5-4bc3-a1c9-6165a2733d2c.png)

fc=1/2π(L/R) =1/(2π(80µH)/(10Ω))= 19.89 kHz

*16.Determine fc para cada una de las posiciones del interruptor en la figura 18-42.
 
 ![image](https://user-images.githubusercontent.com/105687213/187330911-72b19ebc-1b60-4731-8e8a-f9adbf3450c6.png)

Posición 1:

fc=1/2πRC=1/(2π(1kΩ)(0.015µf))=90 µHz

Posición 2:

CT=1/(1/0.015+1/0.01)=0.006 µf

RT=1/(1/3.3+1/2.2)=1.32 kΩ

fc=1/2πRC=1/(2π(1.32kΩ)(0.006µf))=40 µHz

Posición 3:

RT=860Ω+1kΩ=1.86 kΩ

fc=1/2πRC=1/(2π(1.86kΩ)(0.015µf))=0.17 kHz

Posición 4:

fc=1/2πRC=1/(2π(1kΩ)(0.015µf))=90µHz

18.Suponiendo que la resistencia de devanado de las bobinas mostradas en la figura 18-43 es de 10Ω, determine el ancho de banda para cada filtro.
 
a)
![image](https://user-images.githubusercontent.com/105687213/187330970-f49bb27f-d218-4d3d-ac74-8df132283ebd.png)

fo=1/(2π√LC)=1/(2π√((12mH)(0.01µf)))=0.06 mHz

XL=2πfL=2π(0.06mHz)(12mH)=4.52 µΩ

RT=10Ω+75Ω=85Ω

Q=fo/Q=0.06mHz/(4.52µΩ)=13.27 

AB=fo/Q=0.06mHz/13.27=4.52µHz

b)
![image](https://user-images.githubusercontent.com/105687213/187331006-a62a6ba2-6e50-4147-ab36-eeeb72f3c0ac.png)

fo=1/(2π√LC)=1/(2π√((2mH)(0.022µf)))=41.6 µHz

XL=2πfL=2π(41.6µHz)(2mH)=52.27 µΩ

RT=10Ω+22Ω=32Ω

Q=fo/Q=(41.6µHz)/(52.27µΩ)=0.79 

AB=fo/Q=(41.6µHz)/0.79=50µHz

20.Para cada filtro mostrado en la figura 18-44, determine la frecuencia central de la pasabanda. Ignore RW.

a)fo=1/(2π√LC)=1/(2π√((12mH)(0.01µf)))=0.06 mHz

b)fo=1/(2π√LC)=1/(2π√((2mH)(0.022µf)))=41.6 µHz

24.Determine la frecuencia central para cada filtro mostrado en la figura 18-46.
 
a)
![image](https://user-images.githubusercontent.com/105687213/187331092-1298b70e-58f8-43b3-ba66-91c3ac67aa76.png)

fo=1/(2π√LC)=1/(2π√((100µH)(0.022µf)))=9.31 µHz

b)
![image](https://user-images.githubusercontent.com/105687213/187331128-00c02de5-ca6c-46aa-8e2d-e60fb33fb386.png)

fo=1/(2π√LC)=1/(2π√((5mH)(0.047µf)))=90 µHz

26. Si la resistencia de las bobinas de la figura 18-47 es de 8 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent = 50 V?
 
a)
![image](https://user-images.githubusercontent.com/105687213/187331211-95817398-47b2-4a52-8805-39b175c487e6.png)

fo=√(1-〖RW〗^2 C/L)/(2π√LC)=√(1-(8Ω)^2 (6.8µf)/(0.5H))/(2π√((0.5H)(6.8µf)))=86.27 Hz

XL=2πfoL=2π(86.27Hz)(0.5H)=271.02Ω

Q=XL/RW=271.02Ω/8Ω=33.87

Zr=RW(Q^2+1)=8(〖33.87〗^2+1)=9.18kΩ

VsalMax=(R/(R+RW))Vent=(1kΩ/(1kΩ+8Ω))50V=49.60V

VsalMin=(R/(R+Zr))Vent=(1kΩ/(1kΩ+9.18kΩ))50V=4.9V

b)
![image](https://user-images.githubusercontent.com/105687213/187331322-de00e1a8-a041-4d61-a7d8-f9cef1f45d48.png)

fo=√(1-〖RW〗^2 C/L)/(2π√LC)=√(1-(8Ω)^2 (47pf)/(10µH))/(2π√((10µH)(47pf)))= 7.34µHz

XL=2πfoL=2π(7.34µHz)(10µH)=0.46pΩ

Q=XL/RW=0.46pΩ/8Ω=575p

Zr=RW(Q^2+1)=8(〖575p〗^2+1)=8Ω

VsalMax=(R/(R+RW))Vent=(2.2kΩ/(2.2kΩ+8Ω))50V=49.81V

VsalMin=(R/(R+Zr))Vent=(2.2kΩ/(2.2kΩ+8Ω))50V=49.81V

4. Vídeo



5.Conclusiones

• Se concluye que la reactancia capacitiva varía inversamente con la frecuencia y la reactancia inductiva varía directamente con la frecuencia, asi tambien un circuito RLC en serie, la resonancia en serie ocurre cuando XC  XL y la frecuencia a la cual tiene lugar la resonancia se llama frecuencia resonante y se designa mediante fr.

•En un circuito en paralelo domina la reactancia más pequeña porque produce la mayor corriente de rama y conforme se incrementa la frecuencia, XL aumenta y XC disminuye hasta alcanzar un valor donde XL  XC. Éste es el punto de resonancia en paralelo.

• Fnalmente es importe conocer y usar bien las diferentes fórmulas ya que mediante estas  se pueden resolver ejercicios de manera sencilla sin tener ningun dificultad.

6.Bibliografía

Floyd, T. (2007). Principios de circuitos electricos. CDMX, México: Pearson.
