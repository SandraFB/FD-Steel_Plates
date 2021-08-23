# Fallas en planchones de acero

## Resumen

Durante las últimas décadas, el diagnóstico de fallas (FD, por sus siglas en inglés Fault Diagnosis) en planchones de acero inoxidable, ha capturado un mayor interés para la mejora de procesos de manufactura y reducción de costos durante las pruebas de los productos. Además, un sistema de FD correcto e inmediato previene problemas y simplifica servicios de mantenimiento programados. Por lo anterior, las herramientas de reconocimiento de patrones ha capturado la atención para diagnosticar las fallas en planta durante la producción de los lotes. En este ejercicio se clasifican las fallas en los planchones, utilizando la base de datos [Faulty Steel Plates](https://www.kaggle.com/uciml/faulty-steel-plates).

## Acerca de la base de datos

La base de datos presentada es de una investigación de Semeion, en el Research Center of Sciences of Communication. El enfoque principal de esta investigación fue clasificar correctamente los tipos de defectos en la superficie de planchones de acero inoxidable, considerando seis posibles defectos (adicional a "otros"). El vector de entrada contiene la información de 27 indicadores que describen el contorno y la forma geométrica del defecto. Debido a que la información es confidencial, no se tiene mayor información de las variables de entrada. Las últimas siete columnas en la base de datos de entrenamiento, son clases convertidas previamente con one-hot encoding. 


| Variables de entrada      | Clases           |
| ------------- |:-------------:|
| X_Minimum | Pastry|
| X_Maximum  |     Z_Scratch|     
| Y_Minimum| K_Scatch|
| Y_Maximum| Stains|
| Pixels_Areas| Dirtiness|
| X_Perimeter| Bumps|
| Y_Perimeter |      Other_Faults|    
| Sum_of_Luminosity|  |
|Minimum_of_Luminosity||
|Maximum_of_Luminosity||
|Length_of_Conveyer ||
|TypeOfSteel_A300 ||
|TypeOfSteel_A400||
|Steel_Plate_Thickness||
|Edges_Index||
|Empty_Index||
|Square_Index||         
|Outside_X_Index||
|Edges_X_Index||
|Edges_Y_Index ||       
|Outside_Global_Index||
|LogOfAreas||
|Log_X_Index||          
|Log_Y_Index||
|Orientation_Index||
|Luminosity_Index     ||
|SigmoidOfAreas     ||

## Referencias 

[1] Fakhr, M. and Elsayad, A. M. (2012). Steel plates faults diagnosis with data mining models. Journal of Computer Science, 8(4), 506.

[2] Simić, D., Svirčević, V., & Simić, S. (2014, June). An approach of steel plates fault diagnosis in multiple classes decision making. In International Conference on Hybrid Artificial Intelligence Systems (pp. 86-97). Springer, Cham.

[3] Srivastava, A. K. (2019). Comparison analysis of machine learning algorithms for steel plate fault detection. International Research Journal of Engineering and Technology (IRJET), 6(5), 1231-1234.

[4] Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer
Science.

[5] Abdullahi, A., Samsudin, N. A., Ibrahim, M. R., Aripin, M. S., Khalid, S. K. A., & Othman, Z. A. (2020). Towards IR4. 0 implementation in e-manufacturing: artificial intelligence application in steel plate fault detection. Indonesian Journal of Electrical Engineering and Computer Science, 20(1), 430-436.


**Elaborado por Sandra de la Fuente**


