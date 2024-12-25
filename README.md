# exeliklubimiy
import pandas as pd
df_excel = pd.read_excel('Оценки.xlsx')
print(df_excel.head())
print(df_excel.sample(5))
print(df_excel.tail(5))
a=int(input("напиши ка мне номер строки"))
df_excel = pd.read_excel('Оценки.xlsx',index_col=a)
print(df_excel)
