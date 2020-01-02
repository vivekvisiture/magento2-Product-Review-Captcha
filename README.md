<b>Magento2 Product Review Captcha</b>

<p>By using this module you can display magento native captcha on product review form.</p>

1.  <b>Installation:</b><br>
	  Unzip Module files inside app/code folder.<br>
	  Run Below Commands: <br>
	    php bin/magento setup:upgrade
	    

2. <b>Configuration:</b><br>
	 Go threw Admin > Store > Configuration > Customer > Customer Configuration > Captcha tab.<br>
	 Select review to show captcha in review form and Save config.<br>
	 
   	<img src="https://www.emizentech.com/Uploads/Configuration.png" />
   


3. <b>Clean magento cache:</b><br>
	Run Below Commands from magento root folder:- <br>
	php bin/magento cache:clean <br>
	php bin/magento cache:flush
	
4. <b>Frontend View:</b><br>
 	The Captcha will be appear in product review form as shown in below screenshot.<br>
	
	<img src="https://www.emizentech.com/Uploads/PDP.png" />

	 
