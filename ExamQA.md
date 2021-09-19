[課程指南](
https://help.offensive-security.com/hc/en-us/articles/4406327703444-Course-start-guide)

[監考相關Q&A](
https://help.offensive-security.com/hc/en-us/articles/360050299352-Proctoring-Tool-Student-Manual)

[考試指南(務必詳讀)](https://help.offensive-security.com/hc/en-us/articles/360040165632)


- 	[環境：網速建議至少5Mbps下載 1Mbps上傳](https://help.offensive-security.com/hc/en-us/sections/360008126631-Proctored-Exams)

-	[需要準備護照給監考官看](
https://help.offensive-security.com/hc/en-us/articles/360040574491-What-is-expected-of-me-as-a-student-to-participate-in-a-proctored-exam-)

-	[考試時間23小時45分鐘，前15分鐘為準備期](https://help.offensive-security.com/hc/en-us/articles/360040160852-When-does-my-proctored-exam-start-)

-	[考前準備期要求](https://help.offensive-security.com/hc/en-us/articles/360040574991-What-are-the-pre-exam-requirements-the-proctor-must-verify-before-I-start-my-exam-)
使用vpn連上，須執行環境檢查，考試會提供 shell檢查

- 考試限制

	- 禁止使用
		- Spoofing(IP, ARP, DNS, NBNS, etc)
		商業攻擊軟體或服務 (Metasploit Pro, Burp Pro, etc.)
		自動化漏洞揭露工具 (e.g. db_autopwn, browser_autopwn, SQLmap, SQLninja etc.)
		大型弱點掃描工具(e.g. Nessus, NeXpose, OpenVAS, Canvas, Core Impact, SAINT, etc.)
		上述其他類似工具也被禁止
		但可以對任何目標系統使用諸如 Nmap（及其腳本引擎）、Nikto、Burp Free、DirBuster 等工具。
		注意禁止從考試機器下載applicaions,files,source code 到你的本地環境

		- Downloading any applications, files or source code from the exam environment to your local machine is strictly forbidden unless they're necessary for you to compromise the exam machine, and make sure to delete it after completing the exam objectives. For more information, please refer to the https://www.offensive-security.com/legal-docs/ 

	- 以下行為會拿不到分數
		- Point Disqualification
			- You will receive no points for a specific target for the following:
			- Using a restricted tool
			- Using Metasploit Auxiliary, Exploit, or Post modules on multiple machines
			- Using the Meterpreter payload on multiple machines
			- Failure to provide the local.txt and proof.txt file contents in both the control panel and in a screenshot


### 其他注意事項或考試Q&A(我覺得比較重要的)

- 如果網路斷線會發生什麼事情？
	- [vpn會短暫斷線，重連即可，若斷線太長時間會需要重新加入session，如果無法重連請發送請求](https://help.offensive-security.com/hc/en-us/articles/360040161972-What-happens-if-I-get-disconnected-from-the-proctoring-software-)
- 監考軟體停止回應怎麼處理？
	- [重開瀏覽器重新加入連接，通知監考人因停止回應而重啟，如果無法重連請發送請求幫助](
https://help.offensive-security.com/hc/en-us/articles/360040162012-What-happens-if-the-proctoring-software-stops-responding-)

- 可以使用自己的腳本嗎？

	- 說明沒有特別提到，但有說利用類似的禁止使用工具的功能應該不能用，必須要特別注意

	- 自己準備的，如果是公開網路上的必須提供網址:

		Exploit Code
		If you have not made any modifications to an exploit, you should only provide the URL where the exploit can be found. Do not include the full unmodified code, especially if it is several pages long.

		If you have modified an exploit, you should include:

		The modified exploit code
		The URL to the original exploit code
		The command used to generate any shellcode (if applicable)
		Highlighted changes you have made
		An explanation of why those changes were made
- 考試中機器打爛了可以還原機器嗎？
	- 考試中可以還原，最多總計可以還原24次，，開始考試時就全部5台機器是初始還原狀態了

- 監考只會有視訊，螢幕分享，不會有聲音

- [與監考人員溝通有專用聊天視窗](https://help.offensive-security.com/hc/en-us/articles/360040575211-How-do-I-communicate-with-the-proctor-during-the-exam-
)

- [想休息時告知監考人員就好](
https://help.offensive-security.com/hc/en-us/articles/360040575251-Can-I-take-breaks-during-the-exam-
)

- [如果考試中有其他人進入房間，監考官會做紀錄，只要不洩漏只要不洩漏考試詳情就沒關係](
https://help.offensive-security.com/hc/en-us/articles/360040575571-Can-other-people-enter-the-room-when-I-take-my-exam-
)

- [可以向監考人員提問跟監考相關的問題](
https://help.offensive-security.com/hc/en-us/articles/360040162132-What-if-I-have-questions-during-the-exam-can-I-ask-the-proctor-
)

- [webcam與考試機器必須在同一台本機電腦](
https://help.offensive-security.com/hc/en-us/articles/360040576151-Can-I-use-a-separate-machine-for-the-WebCam-feed-
)

- [考試期間可以中途換地點](https://help.offensive-security.com/hc/en-us/articles/360040162352-Can-I-change-locations-during-the-exam-)

- [結束考試務必通知監考人員，回應確認後再按結束](
https://help.offensive-security.com/hc/en-us/articles/360040162392-How-do-I-correctly-close-out-of-my-proctored-exam-session-
)

- [同時最多可以用4個螢幕](
https://help.offensive-security.com/hc/en-us/articles/360040162432-How-many-monitors-or-screens-are-allowed-during-the-exam-
)

- [考試不能錄影](
https://help.offensive-security.com/hc/en-us/articles/360040576311-Can-I-record-my-screen-when-taking-the-exam-
)

- [考試期間使用手機電話注意事項，不能在座位上接聽，考試期間應保持遠離電話](
https://help.offensive-security.com/hc/en-us/articles/360046886732-Can-I-use-my-phone-during-the-exam-
)

- [考試中的設備在考試中不能用於考試以外的其他目的，也不能有其他電子設備](
https://help.offensive-security.com/hc/en-us/articles/4406628296724-Am-I-allowed-to-use-another-devices-for-other-purposes-during-the-exam-
)


- [考試期間不能在考試設備上進行通話和會議](
https://help.offensive-security.com/hc/en-us/articles/4406628301716-Can-I-conduct-video-calls-or-meetings-on-my-exam-machine-during-the-exam-
)


- 電子筆記可以嗎？
	- 沒有特別寫，但是允許的項目有包含[考試設備](https://help.offensive-security.com/hc/en-us/articles/4406621212820-What-are-the-items-that-are-allowed-and-not-allowed-in-my-exam-environment-)，也許可以提前準備，可以問問[考過的人](https://tech-blog.cymetrics.io/posts/crystal/oscp-review/)





