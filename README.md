# t-test : Customer ratings of Paul bakeries in Brussels and Paris

This project analyzes Google Maps customer ratings of Paul bakeries located in Brussels (23 stores) and Paris (13 stores). The goal is to test whether a statistically significant difference exists between the two cities' evaluations.

  📊 Methodology
  
  Data source
  
    Google Maps evaluations (manual extraction)
  
  Statistical tests:
  
    Shapiro-Wilk test (normality check)
    Levene’s test (homogeneity of variances)
    Welch's t-test (due to unequal variances)
    
  
  📈 Results
  
    Normality was not rejected (p > 0.05)
    Homogeneity of variances was rejected (p < 0.05)
    Welch's t-test showed a significant difference (p = 0.0002)
    
  
  ➡️ Conclusion
    
    Paul bakeries in Brussels have significantly higher ratings than those in Paris.

=======================================================================================

Titre : Comparaison des évaluations des boulangeries Paul à Bruxelles et à Paris

Ce projet analyse les évaluations des boulangeries Paul sur Google Maps, à Bruxelles (23 magasins) et à Paris (13 magasins). L’objectif est de déterminer s’il existe une différence significative entre les deux villes.

  📊 Méthodologie
  
  Source des données 
  
    Évaluations Google Maps (relevées manuellement)
    
  Tests statistiques :
  
    Test de Shapiro-Wilk (normalité)
    Test de Levene (homogénéité des variances)
    Test t de Welch (variances inégales)
  
  📈 Résultats
  
    La normalité n’a pas été rejetée (p > 0.05)
    L’homogénéité des variances a été rejetée (p < 0.05)
    Le test de Welch montre une différence significative (p = 0.0002)
  
  ➡️ Conclusion
  
    Les boulangeries Paul à Bruxelles ont une note moyenne significativement plus élevée que celles à Paris.

=======================================================================================

タイトル：ブリュッセルとパリにおけるPaulベーカリーの評価比較

このプロジェクトでは、GoogleマップにおけるPaulベーカリーの評価を分析し、**ブリュッセル（23店舗）とパリ（13店舗）**の間で統計的に有意な差があるかを検証した。

  📊 分析方法
  データソース
  
    Googleマップの評価（手作業で取得）
  
  統計検定：
  
    Shapiro-Wilk検定（正規性の確認）
    Levene検定（等分散性の確認）
    Welchのt検定（分散が異なる場合）
  
  📈 結果
  
    正規性は棄却されなかった（p > 0.05）
    等分散性は棄却された（p < 0.05）
    Welchのt検定では、有意差が確認された（p = 0.0002）
  
  ➡️ 結論
  
    ブリュッセルのPaulベーカリーの評価は、パリよりも有意に高いことが分かった。
