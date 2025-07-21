# Deteksi Objek Menggunakan YOLOv3 dan ESP32-CAM

#### Proyek ini bertujuan untuk mendeteksi berbagai objek dalam gambar yang diambil oleh kamera ESP32-CAM. Proses deteksi dilakukan dengan menggunakan model YOLOv3 yang telah dilatih sebelumnya. Gambar yang diambil oleh ESP32-CAM akan diproses menggunakan OpenCV di Python, di mana gambar tersebut akan mengalami flip horizontal dan vertikal sebelum dilakukan deteksi objek. Objek yang terdeteksi akan ditampilkan dengan bounding box dan label di sekitar objek tersebut.

- [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)
- [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
- [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)
