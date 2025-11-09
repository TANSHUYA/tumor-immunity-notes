# 机体抗肿瘤免疫应答 — 思维导图

```mermaid
mindmap
  root((机体抗肿瘤免疫应答))
    细胞免疫
      CD8+_CTL["CD8⁺ CTL\n识别: pMHC-I\n激活: DC + CD4⁺(IL-2, IL-12)\n杀伤: 穿孔素/颗粒酶; Fas/FasL; TNF"]
      CD4_Th["CD4⁺ Th\n帮助 CTL 激活\n分泌细胞因子→激活 Mφ、NK\n少数直接杀伤"]
      NK["NK 细胞\n识别: MHC I 缺失\n杀伤: 自然杀伤; ADCC (FcγRIII)"]
      Macrophage["巨噬细胞 (Mφ)\n吞噬; TNF-α; ADCC; APC"]
      gamma_delta["γδ T 细胞\n直接杀伤; 分泌细胞因子"]
    体液免疫
      Antibody["抗体 (Ab)\n中和; 调理吞噬; ADCC; CDC; 封闭受体"]
      Complement["补体\nCDC; 调理 (C3b)"]
    非特异性免疫
      Innate["先天免疫要素\nNK / Mφ / γδ T / 细胞因子网络 / 补体"]
    免疫逃逸
      EscapeMechanisms["逃逸机制\n抗原丢失/调变; MHC I 下调; 缺乏共刺激; 分泌抑制因子(TGF-β, IL-10);\n诱导 AICD; 抗凋亡(Bcl-2); 肿瘤微环境(Treg, TAM, MDSC)"]
    免疫治疗
      Checkpoint["检查点抑制剂\n抗 PD-1/PD-L1; 抗 CTLA-4"]
      CellTherapy["细胞疗法\nCAR-T / TCR-T / TIL / LAK"]
      Vaccines["肿瘤疫苗\n主动免疫策略"]
      CytokineTherapy["细胞因子疗法\nIL-2, IFN-α 等"]
      TargetedAb["抗体靶向治疗\nHer2, CD20 等"]
    互作网络
      Network["关键互作\nDC → CD4⁺ Th → CD8⁺ CTL\nCD4⁺ Th → 激活 Mφ / NK\nAb → NK (ADCC)\nAb → 补体 (CDC)\n细胞因子 → 多种细胞激活"]
