
Todos estos modelos se entrenaron usando solo el conjunto de datos de PETS2009-S2L1, a este conjunto de datos de dividió en 5 partes , y las primeras cuatro partes se tomarón, y a ese conjunto se le llamó Train1, y así respectivamente.
Test1 al conjunto sobrante de los 5


*El modelo lstm-dxdy0.h5 es el modelo que se entreno con train1

*El modelo lstm-dxdy1.h5 es el modelo que se entreno con train2

*El modelo lstm-dxdy2.h5 es el modelo que se entreno con train3

*El modelo lstm-dxdy3.h5 es el modelo que se entreno con train4

*El modelo lstm-dxdy4.h5 es el modelo que se entreno con train5

esos modelos fueron con los datos de pets de framerate de 7.5 al cual se le denomina pixel_pos_2-csv"


y los que tienen la palabra simplificado tambien es con pets, solo que con framerate 3.75 frames por segundo
que ese es denominado pixel_pos.csv 




Lo siguiente se realizo con el scrip lstm_dx-dy_variosDatsets.ipynb
Los otros modelos lo que se hizo fue entrenar con 5 conjuntos de datos y el sobrante fue con el que se probo.

Por ejemplo el modelo lstmethhotel.h5 fue entrenado con los conjuntos [eth-univ,pets,ucy-univ,zara1,zara2] y fue probado con eth-hotel 

asi respectivamente con los otros modelos
