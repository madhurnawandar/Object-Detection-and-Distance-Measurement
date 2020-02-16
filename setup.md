{\rtf1\ansi\ansicpg1252\cocoartf2511
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 Menlo-Regular;\f1\fnil\fcharset0 HelveticaNeue-Medium;\f2\froman\fcharset0 Times-Roman;
}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red23\green90\blue226;\red255\green255\blue255;
\red0\green0\blue233;}
{\*\expandedcolortbl;;\csgray\c0;\cssrgb\c10196\c45098\c90980;\cssrgb\c100000\c100000\c100000;
\cssrgb\c0\c0\c93333;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0

\f0\fs30 \cf2 \CocoaLigature0 # Create a python 3 bases virtual env\
python3 -m venv tensor-env\
source tensor-env/bin/activate\
# Download the source repo\
git clone git@github.com:madhurnawandar/Object-Detection-and-Distance-Measurement.git\
cd Object-Detection-and-Distance-Measurement/\
#Download the model\
Download the file 
\f1\fs26 \cf3 \cb4 \expnd0\expndtw0\kerning0
\CocoaLigature1 \outl0\strokewidth0 \strokec3 yolov3.weights 
\f0\fs30 \cf2 \cb1 \kerning1\expnd0\expndtw0 \CocoaLigature0 \outl0\strokewidth0 from \
 {\field{\*\fldinst{HYPERLINK "https://drive.google.com/drive/folders/1nN49gRqt5HvuMptfc0wRVcuLwiNmMD6u"}}{\fldrslt 
\f2\fs24 \cf5 \expnd0\expndtw0\kerning0
\ul \ulc5 \CocoaLigature1 \outl0\strokewidth0 \strokec5 https://drive.google.com/drive/folders/1nN49gRqt5HvuMptfc0wRVcuLwiNmMD6u}}
\f2\fs24 \cf5 \expnd0\expndtw0\kerning0
\ul \ulc5 \CocoaLigature1 \outl0\strokewidth0 \strokec5 \
\

\f0\fs30 \cf2 \kerning1\expnd0\expndtw0 \ulnone \CocoaLigature0 \outl0\strokewidth0 and replace the he existing file in the folder\
# Install python dependencies\
pip install -r requirements.txt\
\
# Run\
python object_detection.py\
\
}