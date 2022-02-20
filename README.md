# hse_hw1_meth



### Задание 1.

[fastqc отчет](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8_cell_SRR5836473_1_bismark_bt2_pe_fastqc.html)

Полученные результаты я сравнивала с [отчетом](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/SRR3414629_1_fastqc.html) о секвенировании РНК, который был взят из одного из прошлых дз.

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  РНК &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 8 Cell
<img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/rna1.png  width="400" height="400"> <img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8cell1.png width="400" height="400">

**Per sequence quality scores:** у образца SRR5836473_1 наблюдается скачок на графике при большом среднем значении качества, однако потом график опять понижается. Это означает, что большинство ридов имеют высокое среднее качество, но очень выкокое имеют меньшее число ридов. У образца SRR3414629_1 такого снижения не наблюдается.

<img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/rna2.png  width="400" height="400"> <img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8cell2.png width="400" height="400">

**Per base sequence content:** у образца SRR5836473_1 пропорции всех оснований почти не изменяются (у ДНК так и должно быть), только в начале рида процент G существенно выше, а процент T существенно ниже. Образец SRR3414629_1 отличается неравномерным распределение в начале рида.

<img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/rna3.png  width="400" height="400"> <img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8cell3.png width="400" height="400">

**Per sequence GC content:** У образца SRR3414629_1 распределение процента GC близко к нормальному распределению (так и должно быть). У образца SRR5836473_1 распределение отличается от нормального. У него существенно преобладает количество ридов с небольшим процентом GC.

<img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/rna4.png  width="400" height="400"> <img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8cell4.png width="400" height="400">



<img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/rna5.png  width="400" height="400"> <img src=https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8cell5.png width="400" height="400">

### Задание 2.

[colab notebook](https://colab.research.google.com/drive/1k0hE1HbzEUAjVCHYPe1QuxYnOPQlw_VD?usp=sharing)

##### a)
![table](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/task_2a_table.png)


##### b)
![table](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/task_2b_table.png)

Бонус: ! ls SRR*.bam | xargs -P 3 -tI{} deduplicate_bismark  --bam  --paired  -o s_{} {}

##### c) 
в ноутбуке
##### d)
[html отчет для 8 Cell](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/8_cell_SRR5836473_1_bismark_bt2_PE_report.html)

[html отчет для ICM](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/icm_SRR5836475_1_bismark_bt2_PE_report.html)

[html отчет для Epiblast](https://github.com/adriadar/hse_hw1_meth/blob/main/images%20and%20reports/epiblast_SRR3824222_1_bismark_bt2_PE_report.html)

+ m bias плот и его описание
##### e)



##### f)
