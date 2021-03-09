# 10902_FCU_AWS_QuickLab-2_EC2
10902_FCU_AWS_QuickLab#2_EC2

主題：建立虛擬機

適用AWS Educate, Starter帳號環境
服務：EC2
作業系統：Windows

# 情境

業務部門因為數據分析需求採購了一套SPSS(含授權)。
SPSS安裝在辦公室的電腦。
每個員工都需要這套數據分析工具進行業務銷售分析。

但是部門相關軟體採購經費拮据，只能負擔起一套SPSS的費用。
身為業務部門中學過雲端的你，馬上在例行會議提出雲端解決分案，架設虛擬機(虛擬電腦/遠端電腦)讓同事遠端登入輪流使用!
請協助部門同事架設虛擬機吧!

# 實施架構


![image](https://user-images.githubusercontent.com/55479898/110415321-a1225e80-80cc-11eb-840c-4335d40c676b.png)


# 實施步驟
![image](https://user-images.githubusercontent.com/55479898/110415401-c3b47780-80cc-11eb-88d3-63999709970c.png)


## Step1：新增EC2執行個體(作業系統：Windows)

1.搜尋EC2

![image](https://user-images.githubusercontent.com/55479898/110415486-ee9ecb80-80cc-11eb-8411-b5c1eadfd71a.png)

2.點選[Instances]

![image](https://user-images.githubusercontent.com/55479898/110415539-05ddb900-80cd-11eb-8dee-78e104063a5c.png)

3.點選[Launch Instance]

![image](https://user-images.githubusercontent.com/55479898/110415602-1c841000-80cd-11eb-8e0d-bc88fb78fedf.png)

4.選擇作業系統(這裡稱為AMI映像檔)


