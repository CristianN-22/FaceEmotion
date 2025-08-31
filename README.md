# FaceEmotion
Archivos necesarios para entrenar el modelo 

#base de datos hecha en Roboflow
!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="EIz2K1NQVyxY2S6qdMy7")
project = rf.workspace("cristian-vision-de-computadora").project("faceemocion-bcsuw")
version = project.version(1)
dataset = version.download("folder")
                
