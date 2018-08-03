CRM 使用框架說明
	1.前端框架thymeleaf
	2.後端框架spring boot 2.0.2
	3.js框架 jQuery
	4.database框架 Hibernate
	5.API使用RESTful設計風格(GET查詢、PUT新增、PUT修改、DELETE刪除)
CRM UI設計注意事項
	1.符合遠傳UI設計，請參考下列網站
	http://flip-test.fareastone.com.tw/redmine/login?back_url=http%3A%2F%2Fflip-test.fareastone.com.tw%2Fredmine%2Fnews%2F12
	2.template使用MIT license的gentelella，請參考
	github:https://github.com/puikinsh/gentelella
	Demo:https://colorlib.com/polygon/gentelella
CRM 測試
	1.單元測試指令 mvn test 預設檔案名稱後加上Test ex:LoginControllerTest.java
	2.執行測試指令 mvn test後會產生落地檔案的swaager document 路徑:./src/docs/....
	3.線上swagger UI文件請在啟動AP後在瀏覽器輸入:http://localhost:8080/CRM/swagger-ui.html
	4.執行覆蓋率測試mvn test 產生jacoco.exec 
	4.產生覆蓋率測試報表 在crm_portal目錄執行mvn jacoco:report 路徑:./CRM/crm_portal/target/site/
	 

