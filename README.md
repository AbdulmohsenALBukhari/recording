# speech to text and text to speech

 -- طريقة الإستخدام --

 واختيار عدد الثواني المراد تسجيل الصوت (transcribe) عند تشيغيل ملف

 text  سوف يبدأ التسجيل ثم سوف يحولها نص ويضعها في ملف  

(voice.mp3) الى ملف (text.txt) سيتم تحويل النص الموجود بملف  convertMp3 عند تشغيل ملف 

مقطع قصير يوضح طريقة الإستخدام البرنامج 
--

![Desktop 2021 07 07 - 19 16 35 02 DVR_Trim](https://user-images.githubusercontent.com/79781915/124795188-73ed9c00-df58-11eb-8865-7403ccee7aca.gif)


# -- محتويات الملفات --

speech.cfg -->  (transcribe) و يتم استداعاه في ملف ibm watson speech to text يحتوى الملف على الاتصال بــ  

transcribe --> يحتوي على كود تحويل الصوت الى نص

convertMp3 --> (MP3) و يحول ملف النص الى  ibm watson text to speech يحتوى الملف على الاتصال بــ 

voice --> الصوت المسجل

text --> يحتوي على النص الذي يتم تخزينه من الصوت المسجل وايضا يتم اخذ النص منه وتحويله لصوت
