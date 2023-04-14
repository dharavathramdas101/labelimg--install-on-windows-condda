# labelimg--install-on-windows-condda

## 1.Step cd "folderpath"

## 2.Step 
    2.1 conda create -n catdog python=3.7 -y
    2.2 conda activate catdog
    
## 3.Step
  conda install pyqt=5
  
 ## 4.Step
   conda install -c anaconda lxml
   
 ## 5.Step
   download labelimg 
   cd "labelimg path"
   
 ## 6.Step
   > dir
   
 ## 7.Step
  > python -m PyQt5.pyrcc_main resources.qrc -o resources.py
  
  after command it will give resources.py
  copy 2 files resources.py and resources.qrc
  past in   libs
  
## 8.Step
  > python labelImg.py
