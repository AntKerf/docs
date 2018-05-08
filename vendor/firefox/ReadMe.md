[License]://creativecommons.org/licenses/by-nc-sa/4.0/deed.ru

����������|��������|������|����|����
---|---|---|---|---
Firefox <sup>[www]</sup>|Release|59.0.0|2018-03-10|all
Firefox <sup>[esr]</sup>|ESR|52.7.0|2018-03-08|all

[www]://www.mozilla.org/ru-ru/firefox/all/#ru "Site"
[esr]://ftp.mozilla.org/pub/firefox/releases/52.7.0esr/win32/ "Extended support"

### ������� ��������

� �������� Firefox ������������ ��������� ����������� ������ Gecko<sup>[*]</sup>, ��������� � ������ ��������� 
WebAssembly<sup>[**]</sup> � �������� ����������. � �������� ������������ ��������� �� ������� ���������, 
�������� ����������, ����� �� ���� ������ � ���������� ������ �� ��������, �������� �������, ���� ��� 
��������� � ��������� ��������.  
����� ������� ����� ��������� ��� ������ *����������*.  
���������� �������������� ������ [Waterfox] ��� [PaleMoon] ��� 64-������ ��. � ���� 2018 �. ����������� ������ 
���������� ������������ �� ������ ESR ��� ������ Firefox ��� Windows XP<sup>[***]</sup>. 

[*]://habr.com/post/313820/ "Rust > Servo > Quantum"
[**]://geektimes.com/post/286718/ "wasm - �������������� ��, ������������� � ��������"
[***]://geektimes.com/post/293773/
[Waterfox]://www.waterfoxproject.org/ "������� � ���������� XUL-����������"
[PaleMoon]://www.palemoon.org/ "������� � ���������� XUL-����������"

---

# ���������� �����������

- ***[habrusers_blocker_gm].user.js*** - ���������� ������������� �� ����� (*user script*)
- ***user.js*** - ������������� ���� ���������� ��������
- ***update_set_ff.vbs*** - ������ ��������������� ���������� ����� *user.js*
- ***ReadMe.md*** - �������� � ������������ �� ������ � ���������

[habrusers_blocker_gm]://github.com/bopoh13/docs/raw/master/vendor/firefox/habrusers_blocker_gm.user.js

# ������������� ���������

### ������ ��������� ����������

1. [Adblock Plus]  
	���������� ��������� ������� ���� �������� ��� ����������� ������� � ������ ���� ��, ��� �������.
	- �������� �������� ������ ������ ������� � �������� EasyList, ���������� 69k ��������, ������� ����� 
		������� ���������� ��� ������.  
		���������� �������������� �������� [AdBlock EdgeList]. ����������� �� ��������� �������������.
	- ������ ������������� ���������� *[Greasemonkey]* ��� ~~*[Stylish]*~~ ��� ����������� ��������� *user 
		script*, ���� ����� ������� �� ������ [�Block Origin].  
		- **�����:** ����������� ������� ����� ����� ���������� � *Stylish*. ����������� 
			�� Userstyles.org �������� **-moz-binding** ����� ��������� JS-��� �� ���������� 
			������������.
2. [Browsec VPN]  
	������������� ���� ��� ����������� ������ ZenMate. ���� ���������� ������� (NL � UK �� 30 ����/���). 
	����� "Smart Settings" ��������� ������� proxy ��� ��������� ������� ��� ��������� ������.
3. [Google Translator]  
	� ������� ����� ���������� ����� ��������� ����� ����� �� ��� ������ ���� ����� ������� ���� 
	��� � ������� ���������� ������. ����� ��������� ���� ���������� �����, ���� ��� ��������.
4. [Octotree]  
	���������� ����������� GitHub � ���� ������.
5. [Video DownloadHelper]  
	����� ������� ������ ������� � �������������� ����� �� ����� ������ ��� YouTube.

[Adblock Plus]://addons.mozilla.org/ru/firefox/addon/1865/
[AdBlock EdgeList]:#������-��-��������-abp-edgelist "Ctrl+Shift+I"
[Browsec VPN]://addons.mozilla.org/firefox/addon/603434/
[Canvas]://geektimes.com/post/284604/#comment_9815366 "SHA-256"
[CanvasBlocker]://addons.mozilla.org/ru/firefox/addon/534930/
[Google Translator]://addons.mozilla.org/ru/firefox/addon/46308/ "�������� ������ �� ��������"
[Greasemonkey]://addons.mozilla.org/ru/firefox/addon/748/ "������ ��� ������� UserJS"
[Octotree]://addons.mozilla.org/ru/firefox/addon/512640/
[Stylish]://github.com/The-OP/Fox/commit/370229fefefb8b724f978ae9641597ca0ad40280 "������ ������� ��� ������ �������� UserCSS"
[Video DownloadHelper]://addons.mozilla.org/ru/firefox/addon/3006/
[�Block Origin]://addons.mozilla.org/ru/firefox/addon/607454/

### ������ �� �������� ABP EdgeList

�������� ����� ���������� � ���������� ���������� "*<kbd>���</kbd> �� ������ -> ��������� -> ����������� -> 
�������� ����� ������ ��������*" ������ ���� � ����� � ����� ����������� **adblock**, ��� ����� ������ � html-����:

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
