# Ucar


#date: 

- 2020/02/08	
- 2020/02/09	改用 TWD97座標


#source: Ucar.ipynb

#purpose:
- 汽車租借站址設置規劃數學模型
- 非線性混整數規劃 轉換為 線性 

#input file: 
- site_twd97.csv	---- 156 site locations with rankings
- PSO_twd97.csv		---- 100 candidate renting spots

#parameter:
- r---- 景點要在站點方圓r範圍內
- n---- 取用幾個景點

#problem:
- 1. r 值調大條小，選擇到的站點都會遠於500公尺。
 
