#pip install pandas

import pandas as pd

#list
#series


s=pd.Series([1,2,3,4,5])
l=[1,2,3,4,5]
s[2]
s1=pd.Series([1,"2","3",4,5])

#dataframes
data={"Name":["Tom","Jerry","Sprike","Mike"],'Age':["28"]}

df = pd.DataFrame(data)

df1=pd.DataFrame(data,index=[1,2,3,4])
df2=pd.DataFrame(data,index=["a","b","c","d"])

df["Name"][0]="Tommy"

#null values
df.info()


#describe
df.describe()

stu_pckg=[6,7,8,4,5,5.5,9,45,2,4.4]
stu_names=["s1","s2","s3","s4","s5","s6","s7","s8","s9","s10"]

student=pd.DataFrames({"Name":stu_names,"package":stu_pckg})
student.describe()

#read_csv

df=pd.read_csv("C:/Users/Mrinal/Music/Iris.csv")
