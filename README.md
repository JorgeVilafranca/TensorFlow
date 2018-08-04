# TensorFlow
TensorFlow está dedicado a Inteligencia Artificial, aprendizaje automático y aprendizaje profundo, desarrollado por google

- Descargar anaconda de https://www.anaconda.com/download/

    - Durante la instalación marcar que añada las rutas de variable.
    - Ventana de comandos, busca los archivos de configuración descargados.
    - Ejecuta los comandos:
    
        - conda env create -f windows_tfdl_env.yml
        - activate tfdeeplearning (nombre que se le ha dado al entorno de trabajo)
        - jupyter notebook
    
    - Se abre el nevegador de internet, pulsar New->python

- Ejercicio de ejemplo:

<div style="border: solid 1px">
import tensorflow as tf<br>
hola = tf.constant("Hola mundo")<br>
sess = tf.Session()<br>
print(sess.run(hola))
</div>
