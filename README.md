**完整報告已做成PTT，詳請見PPT~~**

以下簡單說明關鍵步驟：
**發現高解釋力特徵**
  1. 取得單價元平方公尺中位數
  2. 如果單價元平方公尺 = 空值 且 建物型態 = 工廠
      令單價元平方公尺 =  單價元平方公尺中位數
  3. 如果單價元平方公尺 = 0
      令單價元平方公尺 =  單價元平方公尺中位數
  4. 如果 車位移轉總面積平方公尺=0 且 車位總價元!=0
      則總價元 =( 建物移轉總面積平方公尺 )* 單價元平方公尺 
      如果 車位移轉總面積平方公尺=!0 且 車位總價元=0
      則總價元 =( 建物移轉總面積平方公尺 )* 單價元平方公尺 + 車位總價元
      否則 總價元 =( 建物移轉總面積平方公尺 -車位移轉總面積平方公尺)* 單價元平方公尺 + 車位總價元

![image](https://github.com/user-attachments/assets/aaac9d51-8765-4e62-8cc5-b8ee8b8aa1dc)

資料分析EDA：
![image](https://github.com/user-attachments/assets/b186b284-8d9c-4af7-bab8-c88cb4180cc5)
![image](https://github.com/user-attachments/assets/b7b87798-145e-46af-bc63-283425298127)
![image](https://github.com/user-attachments/assets/607a6784-847b-41cf-a53b-6ce2891c3c5e)
![image](https://github.com/user-attachments/assets/d524fdbb-7427-4642-bb83-913d5322d502)
![image](https://github.com/user-attachments/assets/3d1317ea-050a-484f-8cbf-01ff0263ba37)
