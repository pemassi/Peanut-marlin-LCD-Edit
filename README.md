# Peanut-marlin-LCD-Edit
피넛 marlin 펌웨어를 LCD를 사용할 수 있게 수정한 버전 입니다. <br>
This Peanut Marlin firmware is the modified version to be able to use the LCD controller. <br>
<br>
#펌웨어 컴파일 하기 전에(Before Comfile)
LCD 컨트롤러을 사용하기 위해서는 'U8glib' 라이브러리가 아두이노 IDE에 추가되어있어야 합니다. 'U8glib' 폴더에 있는 'INSTALL.TXT'를 참고해주세요. [U8glib\INSTALL.TXT]<br>
You should install 'U8glib' libaray in Arduino IDE. So, Read 'INSTALL.TXT' in 'U8glib' folder.
<br>
<br>
#업데이트 및 수정 (Update & Edit) - 2015.10.2
* EEPROM을 이용한 설정 값 저장 기능 추가(Set values take additional storage functions that use EEPROM)
Marlin 펌웨어에서 지원하는 EEPROM 저장기능을 활성화 하였습니다. LCD 컨트롤을 이용하여 변경된 다양한 값들을 저장 할 수 있습니다.<br>
It did to enable EEPROM that are supported by storage, firmware Marlin. Lcd control using a modified variety of values can be saved.<br>
* LCD 메뉴 수정(LCD Menu Edit)
불필요한 메뉴들을 제거하고, 자주 사용하는 명령어를 상위 메뉴로 이동하였습니다.<br>
Unnecessary service provider menus and removing the top menu has moved frequently used commands.<br>
* LCD 인코더 문제 해결(Troubleshooting LCD Encoder)
LCD에 있는 인코더를 한 칸 이동했지만 값이 1씩 변하지 않는 문제를 해결하였습니다.<br>
The following code example demonstrates how in lcd a spaces, but value found in the next thing you know, I have solved the problem that doesn't change.<br>
<br>
<br>
Edit by 프매씨(pemassi, ruddbs5301@naver.com, korea) <br>
homepage : http://vmao.tistory.com
