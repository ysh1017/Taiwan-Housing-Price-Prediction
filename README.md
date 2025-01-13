**老師您好，我是排名一報告同學**
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

![image](https://github.com/user-attachments/assets/fe185f91-d089-4f2a-9a55-0898ce11da80)

資料分析EDA：
![image](https://github.com/user-attachments/assets/ca1ad72c-dec2-4679-9949-571365471ef8)
![image](https://github.com/user-attachments/assets/b9709239-3b09-4c79-a827-e753eab055aa)
![image](https://github.com/user-attachments/assets/59bd3ff7-7bab-4a93-8b9d-ffd761815d2b)
![image](https://github.com/user-attachments/assets/7ca200f1-e11e-41eb-a233-3ecf9ca3280f)
![image](https://github.com/user-attachments/assets/fe3d95be-98d4-44d1-91a6-1eca63315bcc)
