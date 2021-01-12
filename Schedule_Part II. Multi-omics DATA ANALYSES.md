# Part II. Multi-omics DATA ANALYSES
###### --本部分主要掌握高通量多维组学数据分析

###### --学习资料搜索(Google;Wikipedia;知乎;简书;公众号)

###### --学习笔记格式:markdown; Rmarkdown

###### --介绍每种组学数据的基本分析流程(组学应用目的;数据集(data/input)，分析pipelines,输出结果解释(output))

## 必学内容

#### 0)High-throughtput data formats and tools

- 负责人: 俊毅/育祥/杨怡

- 学习目标:1.掌握高通量组学数据基本文件格式; 2.掌握高通量组学数据常用分析工具;

  ​                3.掌握Sequence alignment;4.掌握Reads Mapping

- 学习参考资料:  

  清华鲁志老师课题组课件:Lulab_NGS(俊毅)

  PDF file:Course1-NGS data formats and tools-8.29-mengsha(QQ群下载): (俊毅)

  《The Biostar Handbook》(QQ群下载): 
  
  推荐阅读章节:
  
> V DATA FORMATS (俊毅)
  > VI VISUALIZING DATA (杨怡)

  [IGV/UCSC 实践](https://lulab2.gitbook.io/teaching/part-iii.-ngs-data-analyses/1.mapping/1.1-genome-browser) (杨怡)

  IGV可视化乳腺癌重要增强子注释信息(杨怡)
  
  北京大学医学部李婷婷老师课件:PPT file:ucsc数据库介绍-ltt(杨怡)
  
  [Blast实践](https://lulab2.gitbook.io/teaching/part-ii.-basic-analyses/1.seqblast)清华鲁志老师课题组课件:Lulab_Sequence Alignment - Blast(育祥)  
  
  [Mapping实践](https://lulab2.gitbook.io/teaching/part-iii.-ngs-data-analyses/1.mapping)清华鲁志老师课题组课件:Lulab_Reads Mapping - Bowtie(育祥)

#### 1)DNA-seq data analysis
* 负责人:俊毅

* 学习目标：1.掌握DNA-seq数据分析流程;2.掌握外显子组数据分析流程

* 学习参考资料: 

  清华鲁志老师课题组课件:Lulab_DNA-seq and Genomic Features(QQ群下载)

  厦大生科院生物信息培训讲座资料(Training6-WES)(QQ群下载)

#### 2)Chip-seq data analysis
* 负责人:诺琪

* 学习目标：掌握Chip-seq数据分析流程

* 学习参考资料: 

  [Chip-seq实践](https://lulab2.gitbook.io/teaching/part-iii.-ngs-data-analyses/3.chip-seq)清华鲁志老师课题组课件:Lulab_ChIP-seq and Network(QQ群下载)

#### 3)ATAC-seq data analysis
* 负责人: 杨怡

* 学习目标：掌握ATAC-seq数据分析流程

* 学习参考资料:

  厦大生科院生物信息培训讲座资料(Training8_ATACseq) (QQ群下载)
  
  北大李程老师课题组课件:(1)ChengLi_genomics_analysis_13_Chromatin 2020.12;(2)ATAC-seq数据处理及应用（泽嘉）(QQ群下载)
  
  清华鲁志老师课题组课件:Lulab_ATAC-seq(QQ群下载)
    
   Workshop for ATAC-Seq analysis(QQ群下载)

#### 4)RNA-seq and microarray data analysis
* 负责人:  育祥

* 学习目标：掌握RNA-seq与基因芯片数据分析流程

* 学习参考资料:   

  厦大生科院生物信息培训讲座资料(Training5-Sequencing technology& RNA-seq;Course2-RNA-seq_analysis-8.30-mengsha) (QQ群下载)

  北大李程老师课题组课件: ChengLi_genomics_analysis_04_RNA-seq 2020.10(QQ群下载)

  [清华鲁志老师课题组课件与练习](https://lulab2.gitbook.io/teaching/part-iii.-ngs-data-analyses/2.rna-seq) Lulab_RNA-seq and Function Analysis

  [基因芯片处理](https://github.com/scRNA-XMU/Process-the-GEO-microarray-data/blob/main/step1_bulkdata_process.R)

#### 5)Proteome data analysis
* 负责人:雅岚

* 学习目标: 掌握蛋白质组数据分析流程

* 学习参考资料：

  [ProteomeExpert分析R包实践](http://www.github.com/lifeinfo/ProteomeExpert/)

#### 6)Phosphoproteome data analysis

- 负责人: 雅岚

- 学习目标：掌握磷酸化组数据分析流程

- 学习参考资料: 

  [Phosmap分析R包实践](https://github.com/ecnuzdd/PhosMap)      

#### 7)scRNA-seq data analysis 

* 负责人: 啸澳

* 学习目标: 掌握scRNA-seq数据分析流程

* 学习参考资料: 

  厦大生科院生物信息培训讲座资料(Training9_scRNAseq) (QQ群下载)

  北大李程老师课题组课件:ChengLi_genomics_analysis_10_Single-cell 2020.12

  清华鲁志老师课题组课件:Advanced - 10. lecture_scrnaseq_analysis_upload(QQ群下载)

  [Seurat分析R包实践](https://satijalab.org/seurat/)

#### 8)scATAC-seq data analysis

- 负责人: 诺琪

- 学习目标：掌握scATAC-seq数据分析流程

- 学习参考资料:  

  厦大生科院生物信息培训讲座资料(Training10_scATACseq) (QQ群下载)                   

#### 9)Spatial data analysis

- 负责人: 雨娟

- 学习目标：掌握Spatial数据分析流程

- 学习参考资料:  

  [空间转录组综述-单细胞天地公众号](https://mp.weixin.qq.com/s/gh1XCbg-8vinGZP7BbREmg)

​       [空间转录组综述Nature Method](https://mp.weixin.qq.com/s/47iA--HPxbr7DYVVrcPA8A)

#### 10)Image data analysis

- 负责人: 元杰/家志/潘越

- 学习目标：掌握临床病理图像数据分析流程

- 学习参考资料:  

  [人工智能在病理诊断领域中的应用](https://mp.weixin.qq.com/s/VO0_bj1ncbdK4uPqhBHngA) (元杰)

  [基于AI和ML的计算病理学的最新进展](https://mp.weixin.qq.com/s/pYZrcSsKLETfEBYtFmao4g) (元杰)

  [plotly](https://plotly.com/) (元杰)

  [Dash](https://dash-gallery.plotly.host/dash-image-segmentation/ ) (家志/潘越)
