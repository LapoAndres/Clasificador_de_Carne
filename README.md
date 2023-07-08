Trabajo Final
Implementacion de la red neuronal Mobilenetv2 usando keras-tensorflow y programacion de una API en flask para su uso en una aplicacion web

## 1. Preparación del entorno
    $ conda create -n APIDeep python=3.7
    $ conda activate APIDeep
    $ conda install ipykernel
    $ python -m ipykernel install --user --name apiMobile --display-name "apiMobile"
    $ conda install tensorflow-gpu cudatoolkit=10.1
    $ pip install tensorflow
    $ pip install jupyter
    $ pip install keras==2.6.0
    $ pip install opencv-python
    $ pip install matplotlib
    $ pip install numpy scipy Pillow cython matplotlib scikit-image opencv-python h5py imgaug IPython[all]

 ## Caso especial/ si existe ya una version de protobuf que usa mysql-connector-python utiliza la versio
    $pip install protobuf==3.20.3
    
 ## 2. Entrenar la red neuronal
 
    Descargar el repositorio
    Abrir terminal en la carpeta y ejecuta jupyter notebook
    
    $ jupyter notebook
    
    Abre el archivo Practica_Final.ipynb
    
## 3. Probar el API de Flask

    $ python API.py
Resultado

Dirijete hacia tu navegador favorito y escribe "localhost:5000", te permitira ver la pagina web y seleccionar la imagen que desees identificar 


Los resultados de prueba del modelo en el conjunto de pruebas son los siguientes: Precisión de pruebas: 0.885185182094574 Pérdida de pruebas: 5153082013130188 

Recuerda que este es un pequeño clasificador de carne pero la potencia de mobilenetv2 te permite entrenarla con tu propio set de datos para cumplir el obejtivo que desees.

No olvides guardar tu modelo ya entrenado.