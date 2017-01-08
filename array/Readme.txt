Nella PI migliorata ho usato gli array per fare tornare alla divisione sia modulo che resto.
Ho poi aggiunto alcune microistruzioni:
-NEWARRAY che mi permette di creare un nuovo array conoscendo il numero di elementi dell'array (Lo ho usato per creare l'array con quoziente e resto)
-RARRAY che mi copia tutto l'array sullo stack leggendo dallo stack l'indirizzo dell'array e nella posizione zero il numero di elementi dell'array (Lo volevo usare per la stampa ma poi non lo ho usato)
-INVERT che mi legge il numero in cima allo stack e lo sostituisce con il numero stesso negato (Per velocizzare l'inverti)
-SOUT che stampa tutti gli elementi dello stack fino a che non trova un -1 (Per veloizzare il ciclo di stampa)
Ho inoltre provato ad implementare la microistruzione div ma mi sono dovuto arrendere per via del fatto che verso sx posso shiftare solo di un byte e non di un bit
