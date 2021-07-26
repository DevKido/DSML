Create a new env named DSML in D:\Softwares\Anaconda3\envs\

conda create --name DSML python numpy pandas

DSML : conda create --name DSML python numpy pandas matplotlib seaborn statsmodels scipy scikit-learn jupyter notebook tensorflow keras pytorch py-xgboost plotly pydot bokeh

Activate env
conda activate path



---LINK : https://naomi-fridman.medium.com/install-pyspark-to-run-on-jupyter-notebook-on-windows-4ec2009de21f

-----SPARK SETUP------
Download JAVA 8 JDK from https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
ID: pepiwe5608@adeata.com
PASS: JustK1do

INSTALL JAVA
FIRST ONE IS JDK (LATER USED FOR JAVA_HOME) 
SECOND IS JRE

INSTALL ANACONDA. SET SECOND TICK MARK FOR PATH

DOWNLOAD SPARK, EXTRACT TO SPARK FOLDER (LATER USED FOR SPARK_HOME)
PUT WINUTILS IN SPARK BIN
CREATE NEW FOLDER --> tmp\hive

--RUN THIS IN CMD
winutils.exe chmod -R 777 C:\tmp\hive
winutils.exe ls -F C:\tmp\hive
--

SYSTEM ENV VARIABLES

JAVA_HOME -> JAVA JDK MAIN FOLDER
SPARK_HOME;HADOOP_HOME -> SPARK MAIN FOLDER (HAS HADOOP_VERSION_NAME)

SET PATH TO RESPECTIVE BINS


create --name sparks python=3.7 jupyter pyspark