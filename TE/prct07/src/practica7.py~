#!/usr/bin/python
#!encoding: UTF-8
import moduloaproximacion
valores=(10,100,1000,10000)
for valor in valores:
 y=moduloaproximacion.aproximapi(valor)
 print y
k=int(raw_input('Nº de veces que desea se ejecute el programa ')) 
n=int(raw_input('Valor de subintervalos: '))
s=[]
for t in range(1,k+1):
  #!print 'El valor aproximado de pi con 35 decimales es: %.35f' %pi
  aproximacion=moduloaproximacion.aproximapi(n*t)
  print'El valor aproximado de pi es: %f' %aproximacion
  s=s+[aproximacion]
print s
# 1)El número máximo de una t_upla es 8
# 2)Para 9 o más
# 3)No se puede definir mediante notación científica
# 4)Encontramos este tipo de extencion, cuando el programador importa un modulo, genera una version compilada. O si importa una ya interpretada, esta tiene extension .pyc 