20200716_P1_安裝docker及docker-compose過程寫入腳本(.sh)

寫入腳本setting.sh這支程式裡

1.開啟虛擬機器(centos7)，建議使用user進入(建議別使用root)

2.進入後打開終端機

  #開啟終端機輸入
  
	yum install git
  
    git clone https://github.com/og80218/2020_dockercompose_jupyter.git
	
	#下載完成後
	
	cd 2020_dockercompose_jupyter
	
	docker-compose up -d
	
	#啟動完成後，可開啟windows網頁，網址輸入虛擬機器IP:8889，有顯示表示完成。
	
	
#註記:欲修改images，可至資料夾dockerfile目錄下