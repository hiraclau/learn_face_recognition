## Installation
``` sh
  pip install pipenv
  pipenv shell
  conda install -c conda-forge dlib
  pip install cmake
  pip install face_recognition
```

## Commands

``` sh
  face_recognition .\img\known\ .\img\unknown\
  face_recognition --show-distance  true  .\img\known\ .\img\unknown\
  face_recognition --tolerance 0.50  .\img\known\ .\img\unknown\  
  face_recognition  .\img\known\ .\img\unknown\ | cut -d ',' -f2
  face_recognition  --cpus 8 .\img\known\ .\img\unknown\  
```