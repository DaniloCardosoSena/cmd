![Online](https://github.com/user-attachments/assets/815025a0-8476-48ac-9be4-09451c52e302)


set wsc = CreateObject("WScript.Shell")
Do
	'Five minutes
	WScript.sleep(5*60*1000)
	wsc.SendKeys("{F13}")
Loop
