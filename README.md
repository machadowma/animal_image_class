# animal_image_class
Algoritmo que, com base em amostras de imagens de animais fornecidas durante a etapa de treinamento, aprende a reconhecer os animais contidos em imagens. O algoritmo é implementado utilizando python3 e opencv-contrib e aplica os conceitos de Machine Learning, Speeded Up Robust Features (SURF), Bag of Visual Words e Support Vector Machine (SVM).

# Pré-requisito
 * Python3
 * Opencv-contrib

# Testes realizados
Foram realizados testes utilizando 120 imagens adquiridas do Google Images, distribuídas igualmente entre as classes abaixo:
 * cat
 * giraffe
 * human
 * lion

Nos testes realizados, a melhor taxa geral de acerto do algoritmo foi de 60%. Para as classes cat, giraffe, human e lion individualmente, a taxa de acerto foi respectivamente de 70%, 70%, 50% e 50%. Resultados mais precisos tendem a ser alcançados utilizando um conjunto maior de imagens. Contudo, os testes iniciais indicam que o algoritmo é promissor.

# Referências
 * J. Minichino, J. Howse, Learning OpenCV 3 Computer Vision with Python, Packt Publishing Ltd, 2015.
 * https://docs.opencv.org/3.4.0/df/dd2/tutorial_py_surf_intro.html
 * https://docs.opencv.org/2.4/modules/features2d/doc/object_categorization.html
 * https://docs.opencv.org/2.4/doc/tutorials/ml/introduction_to_svm/introduction_to_svm.html
