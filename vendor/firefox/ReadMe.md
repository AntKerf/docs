[License]://creativecommons.org/licenses/by-nc-sa/4.0/deed.ru

����������|��������|������|����|����
---|---|---|---|---
Firefox <sup>[www]</sup>|Release|56.0.0|2017-09-27|all
Firefox <sup>[esr]</sup>|ESR|52.4.0|2017-09-22|all

[www]://www.mozilla.org/ru-ru/firefox/all/#ru "Site"
[esr]://ftp.mozilla.org/pub/firefox/releases/52.4.0esr/win32/ "Extended support"

### ������� ��������

� �������� Firefox ������������ ��������� ����������� ������ Gecko<sup>[*]</sup>, ��������� � ������ ��������� 
WebAssembly<sup>[**]</sup> � �������� ����������. � �������� ������������ ��������� �� ������� ���������, 
�������� ����������, ����� �� ���� ������ � ���������� ������ �� ��������, �������� �������, ���� ��� 
��������� � ��������� ��������.  
����� ������� ����� ��������� ��� ������ *����������*.  
���������� �������������� ������ [Waterfox] ��� 64-������ ��. � ���� 2018 �. ����������� ������ ���������� 
������������ �� ������ ESR ��� ������ Firefox ��� Windows XP<sup>[***]</sup>. 

[*]://habrahabr.ru/post/313820/ "Rust > Servo > Quantum"
[**]://geektimes.ru/post/286718/ "wasm - �������������� ��, ������������� � ��������"
[***]://geektimes.ru/post/293773/
[Waterfox]://www.waterfoxproject.org/ "������� � ���������� XUL-����������"

---

# ���������� �����������

- ***[habrusers_blocker_gm].user.js*** - ���������� ������������� �� ����� (*user script*)
- ***user.js*** - ������������� ���� ���������� ��������
- ***update_set_ff.vbs*** - ������ ��������������� ���������� ����� *user.js*
- ***ReadMe.md*** - �������� � ������������ �� ������ � ���������

[habrusers_blocker_gm]://github.com/bopoh13/docs/raw/master/vendor/firefox/habrusers_blocker_gm.user.js

# ������������� ���������

### ������ ��������� ����������

1. [Adblock Plus] `[e10s]`  
	���������� ��������� ������� ���� �������� ��� ����������� ������� � ������ ���� ��, ��� �������.
	- �������� �������� ������ ������ ������� � �������� EasyList, ���������� 69k ��������, ������� ����� 
		������� ���������� ��� ������.  
		���������� �������������� �������� [AdBlock EdgeList]. ����������� �� ��������� �������������.
	- ������ ������������� ���������� *[Greasemonkey]* ��� ~~*[Stylish]*~~ ��� ����������� ��������� *user 
		script*, ���� ����� ������� �� ������ [�Block Origin].  
		- **�����:** ����������� ������� ����� ����� ���������� � *Stylish*. ����������� 
			�� Userstyles.org �������� **-moz-binding** ����� ��������� JS-��� �� ���������� 
			������������.
2. ~~[Google Translator]~~  
	� ������� ����� ���������� ����� ��������� ����� ����� �� ��� ������ ���� ����� ������� ���� 
	��� � ������� ���������� ������. ����� ��������� ���� ���������� �����, ���� ��� ��������.
3. [Octotree] `[WebExt]`  
	���������� ����������� GitHub � ���� ������.
4. [Video DownloadHelper] `[e10s]`  
	����� ������� ������ ������� � �������������� ����� �� ����� ������ ��� YouTube.
5. ~~[�������� ����]~~  
	���������� �������� ��� ���������� �������� �� ������ *drom.ru* (�� �������� 
	� ����������� �������� �������������� ���� � ����������� � ��������).

[Adblock Plus]://addons.mozilla.org/ru/firefox/addon/1865/
[AdBlock EdgeList]:#������-��-��������-abp-edgelist "Ctrl+Shift+F -> �������� ��������..."
[Google Translator]://addons.mozilla.org/ru/firefox/addon/46308/
[Greasemonkey]://addons.mozilla.org/ru/firefox/addon/748/ "[e10s] ������ ��� ������� UserJS"
[Octotree]://addons.mozilla.org/ru/firefox/addon/512640/
[Stylish]://github.com/The-OP/Fox/commit/370229fefefb8b724f978ae9641597ca0ad40280 "������ ������� ��� ������ �������� UserCSS"
[Video DownloadHelper]://addons.mozilla.org/ru/firefox/addon/3006/
[�Block Origin]://addons.mozilla.org/ru/firefox/addon/607454/
[�������� ����]://addons.mozilla.org/ru/firefox/addon/542220/

### ������ �� �������� ABP EdgeList

�������� ����� ���������� � ���������� ���������� "*<kbd>Ctrl+Shift+F</kbd> -> �������� ��������...*" ������ 
���� � ����� � ����� ����������� **adblock**, ��� ����� ������ � html-����:

`<a href="abp:subscribe?title=AdBlock%20EdgeList&location=https%3A%2F%2Fgithub.com%2Fbopoh13%2Fdocs%2Fraw%2Fadblock%2Fvendor%2Ffirefox%2Fadblockedge.txt">AdBlock EdgeList</a>`

### �������������� �����������

������ � �������� ������ ���������� ������-����� "������� � ��� ��� ������". � ������ ������ ��������� 
������ ���������� �������� �� ������ ��� ����������, ����� �������������� ����� [�������] (��� Windows 7 
��������� ���������� ������ [Speech Platform]) ���� ������������� ���������� [TTS] (������ �� 0,1 ��).  
MS Word ����� ������� ��������������� ������ (� "*���������� �����*" � ������ "*������� �� �� �����*" 
������� "*�����������*").

[�������]://support.mozilla.org/ru/kb/otvet-na-forume-ustanovka-golosov-dlya-windows-10
[Speech Platform]://www.microsoft.com/en-us/download/details.aspx?id=16789
[TTS]:http://mytts.forum2x2.ru/f10-forum "Text-To-Speech ������"

# 
