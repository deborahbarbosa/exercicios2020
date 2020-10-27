# exercicios2020
I've been practicing this year. So here I'm gonna show how and what I'm learning. Just to create memories &lt;3 


#primeiro: funcionamento de um semáforo feito no nim. inspiração do curso women can code.

proc semaforo(sinalanterior: char):
  
  char=
  
  if sinalanterior == 'V':
    result = 'A'
  elif sinalanterior == 'A':
    result = 'P'
  elif sinalanterior == 'P':
    result = 'V'
  
echo semaforo('P')
echo semaforo('V')
echo semaforo('A')
