# Proyecto 6: Visión por Computadora

Este proyecto implementa un sistema de autenticación biométrica utilizando reconocimiento facial mediante inteligencia artificial. El sistema permite registrar usuarios y verificar su identidad utilizando la cámara del dispositivo y modelos de reconocimiento facial proporcionados por DeepFace.
El objetivo principal es reemplazar el uso tradicional de contraseñas mediante verificación facial segura.

Se deben tener instaladas las librerias y paquetes siguientes:
Python 3.10
DeepFace
OpenCV
TensorFlow
Numpy

Se deberá crear un entorno viertual dependiendo si es macOS o Windows
Funcionamiento:
1. El usuario ingresa su nombre
2. El sistema activa la cámara
3. Después de una cuenta regresiva, se captura el rostro
4. La imagen es almacenada en la carpeta caras_registrdas

El sistema captura una nueva imagen del usuario, deepface compara el rostro capturado contra los rostros registrados, si existe coincidencia facial, se da un acceso concedido, en caso contrario será un acceso denegado.

El sistema utiliza embeddings faciales generados mediante DeepFace y modelos de redes neuronales convolucionales para realizar comparaciones biométricas entre rostros.
La verificación facial se realiza utilizando el backend RetinaFace para detección robusta de rostros.
La verificación facial se realiza utilizando el backend RetinaFace para detección robusta de rostros.


NOTAS IMPORTANTES:
1. La primera ejecución puede tardar algunos minutos debido a la descarga automática de modelos de DeepFace/TensorFlow.
2. La primera ejecución puede tardar algunos minutos debido a la descarga automática de modelos de DeepFace/TensorFlow.
3. El proyecto fue desarrollado y probado en macOS utilizando Python 3.10.

Autor
Carlos Daniel Velazquez Saldaña
-- [DVX] --
