# 南華大學軟體工程-期中報告-用例分析與設計
## 組員:11024254蔡尚原 11024255蔡尚倫
### 一.實驗目的
#### 通過"網路教學系統"UML建模過程掌握用力分析與設計方法
### 二.實驗環境
#### PowerDesigner16開發環境
### 三.實驗任務
#### 系統的功能需求主要包括以下幾個方面:
(```學生可以登錄網站瀏覽訊息、查找信息和下載文件。
教師可登入網站輸入課程簡介、上傳課件文件、發布消息、修改和更新消息。
系統管理員可以對頁面維護以及批准用戶的註冊申請。
必須包含:繼承、包含和擴展關係，鼓勵分析網路教學系統的需求，增加合理用例。)
### 四.實驗步驟
#### 分析實驗任務內容，完成系統需求分析，並利用UML完成用例建模，主要包括:
1.尋找系統所有參與者(Ator)
2.從參與者出發，尋找所有用例(UseCase)(鼓勵在任務基礎上發散考慮增加合理的用例)
3.對每個參與者選擇一個用例，撰寫格式完整的用例描述
4.建構完整的用例圖。
### 五.實驗作業
#### 1.尋找系統所參與者(Actor)
參與者(Actor):學生、教師、系統管理員
#### 2.從參與者出發，尋找所有用例(UseCase)
##### (1)學生用例
1.泛化是一種繼承關係，學生繼承用戶類。
2.關聯是學生可以登錄、登錄網站瀏覽課程、查找課件、下載課件和觀看視頻。
3.包含是學生登錄後才可以進行相關操作。
4.擴展是登錄前提條件需要先註冊、輸入驗證碼和找回密碼。
image

(2)教師用例
1.泛化是一種繼承關係，教師繼承用戶類。
2.關聯是教師可以登錄、查看教學心得、修改教學心得、發布教學心得、上傳課件和上傳教學視頻。
3.包含是教師登錄後才可以進行相關操作。
4.擴展是登錄前提條件需要先註冊、輸入驗證碼和找回密碼。
image

(3)系統管理員用例
1.泛化是一種繼承關係，系統管理員繼承用戶類。
2.關聯是系統管理員可以登錄系統、對網站頁面維護、批准用戶的註冊申請和審核不合法課件。
3.包含是系統管理員登錄後才可以進行相關操作。
image

3.建構完整的用例圖。
image

### 六.實驗結果與分析
1.掌握用例關聯(繼承)、泛比、包含、擴展的使用，可以熟練運用PowerDesigner16開發環境繪畫用例圖。
2.包含(include)、擴展(extend)、泛化(Inheritance)的區別:
條件性:泛化中的子用例和extend中的被包含的用例會無條件發生，而extend中的延伸用例是有條件的。
直接性:泛化中的子用例和extend中的延伸用例為參與者提供直接服務，而include中被包含的用例為參與者題工間接服務。
對extend而言，延伸用例並不包含基礎用例的內容，基礎用例也不包含延伸用例的內容。
對Include而言，子用例包含基礎用例的所有內容及其和其他用例或參與者之間的關係。
### 參考資料
[实验二、UML建模之用例分析与设计](https://liush.blog.csdn.net/article/details/123818285?spm=1001.2101.3001.6650.10&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-10-123818285-blog-124869427.235%5Ev43%5Econtrol&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-10-123818285-blog-124869427.235%5Ev43%5Econtrol&utm_relevant_index=19)
