### Data warehouse & Data Mining 2021

### Name : Torfun Phongphidet
### ID : 623021048-3
### สาขา : สารสนเทศสถิติ
### ชื่อกลุ่ม : วากาเมะ
### สมาชิกในกลุ่ม 
### 1.นายปริชญา หงส์ทองคำ 623020528-4
### 2.นายมันนี่ พิทักษ์ 623020532-3	
### 3.นายสิทธัตกะ จรัสแสง 623020541-2	
### 4.นายชณะชัย อิสระกูล  623021045-9
### 5.นางสาวทอฝัน พงษ์พิเดช 623021048-3

#สารบัญเนื้อหา

วิชา Data Mining and Data Warehouse

* บทที่ 1 [Introduction ](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/HW1)ประกอบด้วยหัวข้อ ดังนี้

  * ทำไมต้องทำเหมืองข้อมูล 
  * เหมืองข้อมูลคืออะไร 
  * มุมมองหลายมิติของเหมืองข้อมูล 
  * สามารถขุดเเหมืองข้อมูลที่ไหนได้บ้าง 
  * รูปแบบหรือทิศทางของข้อมูล 
  * ควรใช้เทคโนโลยีประเภทใด? 
  * แอพพลิเคชั่นเป้าหมาย
  * ความสำคัญในการทำเหมือง
  * ประวัติความเป็นมา
  * สรุป 
  
* บทที่ 2 Getting to Know Your Data ประกอบด้วยหัวข้อ ดังนี้

  * [Basic Python](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Data102_(Chapter2).ipynb)
    * Casting
    * Data Structure
    * List
    * Loop
    * Condition
    * Function
  * [Plot Data](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Data102_(Chapter2).ipynb)
    * Besic Data
    * การตรวจสอบตารางข้อมูลโดยใช้ .head()&.tail()
    * Boxplot
    * Time Series Plot
  * [Visualizetion](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Data_Visualization.ipynb)
    * Scatter plot
    * Plot
    * Bar chart
    * Histogram
  * [Distance Numpy](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Distance_Numpy.ipynb)
    * Numpy Array
    * Distance Matrix

* บทที่ 3 [Data Preprocessing](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Data_Preprocessing(Chapter_3).ipynb) ประกอบด้วยหัวข้อ ดังนี้


  * Meta Data
  * การจัดการข้อมูลในตารางก่อนนำไปวิเคราะห์
    * การชี้ข้อมูลในตาราง
      * ชี้แบบธรรมดา
      * ชี้แบบ .iloc[
    * Missing Value
      * Handle Missing Value 1 (ลบค่า Missing)
      * Handle Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
      * Handle Missing Value 2
      * Handle Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handle Missing Value 4 (แทนด้วยค่ากลาง)
      * Handling Missing Value 5 (แทนด้วย column ใกล้เคียง)
    * PANDA
      * Select data by values [PD]
      * ใช้ & (and) และ | (or) ในการรวม list ของ boolean
    * Quiz 4
      * การต่อตารางแนวแกน Y [PD]
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
      * การเรียงข้อมูล[PD]
      * utlier
    * Quiz 5
      * Pandas' looping(.iterrows)
    * การรวม 2 ตารางโดยใช้ .merge()
      * Group by (pandas)
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD]การสร้างตาราง
      

* บทที่ 4 [Data Warehousing and On-line Anaalytical Processing](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/%E0%B8%9A%E0%B8%97%E0%B8%97%E0%B8%B5%E0%B9%884.pdf) ประกอบด้วยหัวข้อ ดังนี้
 
  * Basic Data Warehouse
    * อะไรคือคลังข้อมูล
    * วัตถุประสงค์
    * การบูรณาการ
  * Data Cube and OLAP
    * OLTP vs. OLAP
    * Data Cubes
    * Conceptual Modeling of Data Warehouse
  * การออกแบบ และการใช้งานคลังข้อมูล
  * ความสำคัญของคลังข้อมูล


* บทที่ 5 [Association_Rules](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Chapter6_Association_Rules.ipynb) ประกอบด้วยหัวข้อ ดังนี้

  * ความหมาย
  * Besic Concepts
    * Plot graph of Itemsets
    * การแก้ไขคอลัมน์ข้อมูล
    * Frequence Itemsets to Association Rule
  * Efficient Pattern Mining Methods
    * Apriori
    * Support


* บทที่ 6 Classification ประกอบด้วยหัวข้อ ดังนี้

  * [Desition Tree](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Chapter_7_Classification_(Decision_Tree).ipynb)
    * Train Model
    * plot tree
    * Evaluation
    * Random
    * Advanced Tree
    * TEST
  * [KNN](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Chap7_Classification_(KNN_NN).ipynb)
    * Split Data
    * Train Model
    * Retrain & Evaluate
    * Neural Network
  * [Evaluation](https://github.com/proditor002/DWDM21_/blob/176ededa32c3e418cedc9e9a3ce679dea4e68d02/Chap7_Classification_(Evaluation).ipynb)
    * Split Data หรือ แบ่ง Data
    * สร้าง Model ทำนาย
    * Evaluation

* บทที่ 7 [Clustering](https://github.com/proditor002/DWDM21_/blob/56148af64d6e442a850bdd51884bca53a8da6091/Chap8_Clustering.ipynb) ประกอบด้วยหัวข้อ ดังนี้

  * K-means
    * Generate Data
    * Clustering
    * Example Application (Color Quantization)

* โครงงานกลุ่ม [Project](https://github.com/proditor002/DWDM21_/blob/209dfaa13cfd73a77205a7e3ff2fb8a1d8dfe5b5/Project%20for%20Group.ipynb)
 * การนำเข้าข้อมูล , แหล่งที่มาข้อมูล
     * ดูว่าข้อมูลมี data missing
       * สรุปข้อมูลเป็นรายคอลลัมม์ว่ามี missing
       * Drop missing value
       * ตรวสจสอบเมื่อลบออกไปแล้วตรวจสอบว่ายังไม่ข้อมูลที่หายไปหรือไม่
       * Percent of missing data from dropna
     * รวมตาราง
       * ตรวจสอบดูการลบข้อมูลที่ซ้ำกัน
     * Data Mining
       * สร้างตารางที่ใช้ในการดู challenge
       * สร้างตารางที่ค่าเฉลี่ยนประชากรมากกว่า 40
       * แปลงให้ข้อมูลอยู่ในรูปแบบเป็น transaction
     * apyori
       * ขั้นตอนติดตั้ง apyori
       * เป็นการเรียกใช้ฟังก์ชัน apriori
       * ผลลัพธ์ที่ได้จากการทำ Associantion ซึ่งรายละเอียดจะอยู่ที่ summary
       * SUMMARY
       * Plot กราฟ เพื่อดุค่าของข้อมูลผลเฉลี่ยในแต่ละจังหวัด
     * Classification
       * ทำการดูว่าประเภทของระบบใดในแต่ละภาคมีการใช้มากสุด
       * กำหนดค่า X และ Y
       * Decision Tree
       * KNN
       * Neural Network
       * วาดกราฟต้นไม้
     * Visulization
  * สไลด์นำเสนอ [Slide Present](https://github.com/proditor002/DWDM21_/blob/209dfaa13cfd73a77205a7e3ff2fb8a1d8dfe5b5/%E0%B8%AA%E0%B9%84%E0%B8%A5%E0%B8%94%E0%B9%8CDW.pdf)
