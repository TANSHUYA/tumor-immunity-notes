mindmap
  root((机体抗肿瘤免疫应答))
    细胞免疫
      CD8+_CTL["CD8⁺ CTL\n识别: pMHC-I\n激活: DC + CD4⁺ Th (IL-2, IL-12)\n杀伤: 穿孔素/颗粒酶; Fas/FasL; TNF"]
      CD4_Th["CD4⁺ Th\n激活 CTL\n分泌细胞因子→激活 Mφ、NK\n部分可直接杀伤"]
      NK["NK 细胞\n识别: MHC I 缺失肿瘤\n杀伤: 自然杀伤; ADCC (FcγRIII)"]
      Macrophage["巨噬细胞 (Mφ)\n吞噬; 分泌 TNF-α\nADCC; 抗原提呈 (APC)"]
      gamma_delta["γδ T 细胞\n直接杀伤; 分泌细胞因子"]
    体液免疫
      Antibody["抗体 (Ab)\n中和; 调理吞噬; ADCC; CDC; 封闭受体"]
      Complement["补体系统\nCDC; 调理作用 (C3b)"]
    非特异性免疫
      Innate["NK / Mφ / γδ T / 补体 / 细胞因子网络\n先天防御作用"]
    免疫逃逸
      EscapeMechanisms["肿瘤免疫逃逸机制\n抗原丢失或调变\nMHC I 下调\n缺乏共刺激信号\n分泌抑制因子 (TGF-β, IL-10)\n诱导 AICD\n表达抗凋亡分子 (Bcl-2)\n免疫抑制微环境 (Treg, TAM, MDSC)"]
    免疫治疗
      Checkpoint["免疫检查点抑制剂\n抗 PD-1/PD-L1\n抗 CTLA-4"]
      CellTherapy["细胞治疗\nCAR-T / TCR-T / TIL / LAK"]
      Vaccines["肿瘤疫苗\n激活特异性免疫反应"]
      CytokineTherapy["细胞因子疗法\nIL-2, IFN-α 等"]
      TargetedAb["抗体靶向治疗\nHer2, CD20 等单抗"]
    互作网络
      Network["免疫细胞互作\nDC → CD4⁺ Th → CD8⁺ CTL\nCD4⁺ Th → 激活 Mφ / NK\nAb → NK (ADCC)\nAb → 补体 (CDC)\n细胞因子 → 激活多种免疫细胞"]

%% 定义浅蓝色样式
classDef lightBlue fill:#cce6ff,stroke:#3399ff,stroke-width:1px,color:#000,font-size:12px,padding:6px;

%% 给所有节点应用浅蓝色
class CD8+_CTL,CD4_Th,NK,Macrophage,gamma_delta,Antibody,Complement,Innate,EscapeMechanisms,Checkpoint,CellTherapy,Vaccines,CytokineTherapy,TargetedAb,Network lightBlue;
