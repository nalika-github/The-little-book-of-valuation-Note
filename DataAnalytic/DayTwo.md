# What is Data Science
Data Science + Math + Business

### Simple step of Data Analytics
1. What happen? (Descritptive Analytics)
2. Why did it happen? (Diagnostic Analytics)
3. What will happen? (Predictive Analytics)
4. How can we make happen? (Presciptive Analytics)

## Machine learning (ML)
### 1. SuperVised Learning -> there are teachers
- Definition: Trained on labeled data
- Application: classification tasks regression tasks

- Note: What is regression (เป็นการนำเอาข้อมูลที่เก็บไว้ในอดีตมาทำนายแนวโน้มข้อมูลที่จะเกิดขึ้นในอนาคตโดยใช้รูปแบบสมการเชิงเส้น (Linear) โดยใช้วิธีการหาความสัมพันธ์ของตัวแปร 2 ตัวขึ้นไป (หรือที่รู้จักกันในคำแบบเท่ ๆ ว่า สหสัมพันธ์ (Correlation)) โดยเราจะต้องระบุให้ชัดเจนว่าตัวแปรใด คือ ตัวแปรอิสระ/ตัวแปรต้น (กำหนดเป็นค่า X) และตัวแปรใด คือ ตัวแปรตาม (กำหนดให้เป็น y))

- Note: Supervised Learning หมายถึงกระบวนการในการสอนอัลกอริทึมให้เรียนรู้จากข้อมูลที่มีการติดป้ายกำกับ (labeled data)ซึ่งหมายความว่าข้อมูลที่ใช้ฝึกสอนจะมีคำตอบที่ถูกต้องแนบมาด้วย เรียกว่าเป็นการ “มีครู” เพราะมีคำตอบที่ถูกต้องอยู่แล้ว

- Note: ตัวอย่างของ Supervised Learning: เรามีข้อมูลของอีเมลแต่ละฉบับ และมีการระบุว่าอีเมลนั้นเป็น "สแปม" หรือ "ไม่ใช่สแปม" นี่คือข้อมูลที่มีการติดป้ายกำกับ
อัลกอริทึมจะถูกฝึกให้รู้จักแยกประเภทอีเมลโดยใช้ข้อมูลนี้ เมื่อฝึกเสร็จแล้ว เราจะสามารถให้อัลกอริทึมทำนายได้ว่าอีเมลฉบับใหม่เป็นสแปมหรือไม่

### 2. Unsuptervised Learning -> there aren' teachers
- Definition: without labeled outputs, identify patterns, structures, or relationships
- Application: clustering, grouping, dimensionality reduction

### 3. Reinforcement Learning -> give reward to reinforement the college behaviour

## Types of Data (How we classify data)
### 1. structured -> able to define as a table (CSV, JSON)
- Customer Information
- Transaction reords
- Inventory management

### 2. unstructured -> unable to define as a table
- Social Media Posts
- Customer Reviews and Feedback
- Emails and Chat Msg
- Audio Recordings
- image and video file

For the unstructure data we have to use the special tool to manage this kind of data we may gonna know those tools in the next session.

## Numerical vs. Categorical Data
1. Numerical -> able to calcurate, cout, measured
- Continuous
- Discrete
- Quantitative data -> Histograms, Scatter Plots.
- Time Series data -> Line chart.
- Text Data -> word clound, pairf plot, heat map.

2. Categorical Data  -> unable to calcurate, cout, measured
- Norminal: No inherent order ?? งง
- Ordinal: Ordered Categories ?? งง
- Quantitative data -> Bar Charts ,Pie Charts

## Type of data in Clustering
1. Quantitative (Numerical) Data.
- Examples: Age, income, weight, height
- Clustering Approach:
- - Algoritums ofther use distance measures like Euclidean or Manhattan distances.
- - Example Grouping customers based on their income and age.
2. Quatitative (Categorical) Data
- Examples: Bender, profuct type, education level.
- Clustering ........................ ตามไม่ทัน

## Types of Data in Classification 
1. Numerical Data(Quantotative)
- Classification Approach:
- - Algorithms often rely on distance metrics, linear relationships, or distribution- based techniques.
- Example:
- - Predictng wheter a customer will churm based on their monthly spending.

2. Categorical Data (Qualitative)
- Classification Approach:
- - Categorical features are usually converted into numerical formats
- Example: Categorical Encoding
- - Size {S, XS, L, M, XL} {1, 2, 3, 4, 5}.
- - Color RGB.

## Data Science Use Case
- Example: Credit Risk Modeling.
- Example: Medicense given.
- Example: framework of fraud detection.
- Example: Quality control of food packages

## Data Science Process
1. Problem Definition
2. Data Collection
3. Data Cleaning
4. Data Exploration -> find the relation of the data
5. Data Visulaization
6. Data Clustering Patten Discovery (Optional)
7. Data Classification Regression (Optional)


