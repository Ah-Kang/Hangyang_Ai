anlysis.ipynb 는 [TCGA 암 조직 vs 암 주변 조직] 발현량 급증 Top 20 유전자id 뽑은 후 
id에 해당하는 gene symbol을 나타낸 것
----

make_dataset.ipynb는 ai가 학습하기 쉽도록 데이터 셋을 만들어주기 위해 만들었음
ML_Ready_Dataset.csv가 학습하기 위한 해당 데이터 

---

mogo.ipynb는 학습용 데이터 (ML_Ready_Dataset.csv)와 유전자 수치 데이터를 비교해서 실제 암인지 정확도를 체크함(정확도 100%가 나왔으나 정말인지는 잘 모르겠음)