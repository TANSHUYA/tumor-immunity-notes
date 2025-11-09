# 🧬 机体抗肿瘤免疫应答 — 思维导图

```mermaid
mindmap
  root((机体抗肿瘤免疫应答))
    细胞免疫
      CD8+_CTL["CD8⁺ CTL<br>识别: pMHC-I<br>激活: DC + CD4⁺ Th (IL-2, IL-12)<br>杀伤: 穿孔素/颗粒酶; Fas/FasL; TNF"]
      CD4_Th["CD4⁺ Th<br>激活 CTL<br>分泌细胞因子→激活 Mφ、NK<br>部分可直接杀伤"]
      NK["NK 细胞<br>识别: MHC I 缺失肿瘤<br>杀伤: 自然杀伤; ADCC (FcγRIII)"]
      Macrophage["巨噬细胞 (Mφ)<br>吞噬; 分泌 TNF-α<br>ADCC; 抗原提呈 (APC)"]
      gamma_delta["γδ T 细胞<br>直接杀伤; 分泌细胞因子"]
    体液免疫
      Antibody["抗体 (Ab)<br>中和; 调理吞噬; ADCC; CDC; 封闭受体"]
      Complement["补体系统<br>CDC; 调理作用 (C3b)"]
    非特异性免疫
      Innate["NK / Mφ / γδ T / 补体 / 细胞因子网络<br>先天防御作用"]
    免疫逃逸
      EscapeMechanisms["肿瘤免疫逃逸机制<br>抗原丢失或调变<br>MHC I 下调<br>缺乏共刺激信号<br>分泌抑制因子 (TGF-β, IL-10)<br>诱导 AICD<br>表达抗凋亡分子 (Bcl-2)<br>免疫抑制微环境 (Treg, TAM, MDSC)"]
    免疫治疗
      Checkpoint["免疫检查点抑制剂<br>抗 PD-1/PD-L1<br>抗 CTLA-4"]
      CellTherapy["细胞治疗<br>CAR-T / TCR-T / TIL / LAK"]
      Vaccines["肿瘤疫苗<br>激活特异性免疫反应"]
      CytokineTherapy["细胞因子疗法<br>IL-2, IFN-α 等"]
      TargetedAb["抗体靶向治疗<br>Her2, CD20 等单抗"]
    互作网络
      Network["免疫细胞互作<br>DC → CD4⁺ Th → CD8⁺ CTL<br>CD4⁺ Th → 激活 Mφ / NK<br>Ab → NK (ADCC)<br>Ab → 补体 (CDC)<br>细胞因子 → 激活多种免疫细胞"]
