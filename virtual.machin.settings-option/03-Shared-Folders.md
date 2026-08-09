# Share folder between host(windows)&guest(virtual os)


### همانطور که از اسمه فایل مشخصه این قسمت میریم درمورد این صحبت کنیم که چجوری میشه از هاست (host)(windows)یا سیستم عامل اصلی نصب رویه سیستم خودمون فایلی رو رویه اون سیستم عاملی که رویه ماشین مجازی(guest) است به اشتراک بزاریم. 
## قبل شروع==>هاست یعنی میزبان واینجا ویندوز اون سیستم عامل میزبان یا هاست است گست هم میشه مهمان و اینجا اون سیستم عامل لینوکس مهمان است رویه هاست ما.

#### کارهایی که باید قبل رفتن به ترمینال بکنید:


- 1Edit Virtual Machine Settings: Open the virtual machine settings.
- 2Select Options: In the settings window, you will see two tabs at the top: Hardware and Options. Click on the Options tab.
- 3Configure Folder Sharing: Navigate to the “Shared Folders” section. You will see three modes:
Disable
Always enabled
Enable until next power off or suspend
Click on “Always enabled”.
- 4Add Folder: Click the Add button and select the folder you want to share from your host machine.

![shared folder location](option-image/Screenshot%20(308).png)
