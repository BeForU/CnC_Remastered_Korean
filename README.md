# CnC_Remastered_Korean
Command and Conquer의 한글화를 위한 저장소입니다. C&C리마스터의 한글화는 이 저장소의 도움 없이도 단 두 가지 툴만으로 번역이 가능하며, 협업 또는 개인적인 작업의 히스토리를 남기기 위해 만들었습니다.

# 한글화 방법

## 언어 파일 추출
C&C 리마스터 설치 폴더의 DATA 폴더 안에는 CONFIG.MEG 파일이 있습니다. 이 파일은 다음의 툴로 열 수 있습니다.

- MEG Editor(https://modtools.petrolution.net/tools/MegEditor)
- OS BIG Editor(https://www.ppmsite.com/osbigeditorinfo)

파일을 연 뒤 DATA\TEXT\MASTERTEXTFILE_EN-US.LOC 파일을 추출하시면 됩니다.

## 언어 파일의 편집
추출한 MASTERTEXTFILE_EN-US.LOC 파일은 확장명을 .DAT로 변환하시면 다음의 툴로 내용을 편집할 수 있습니다.

- String Editor(https://modtools.petrolution.net/tools/StringEditor)
- Empire at War Text Editor(https://www.moddb.com/mods/first-order-at-war/downloads/empire-at-war-text-editor-public-beta)

전자는 편집 히스토리 기능을 사용할 수 있고, 후자는 XML로의 추출을 지원하여 에디터가 아닌 다른 툴을 이용해 번역하기 유리한 장점이 있습니다.

## 한국어 글꼴 교체 방법
(이 저장소에 이미 적당한 무료 글꼴이 추가된 언어파일이 있습니다. 여기서 가져다 쓰셔도 됩니다.)

기본적으로 C&C 리마스터는 구글과 어도비가 개발한 NotoSansCJK 글꼴을 내장하고 있습니다. 이 글꼴은 중국어를 위해 탑재된 듯 하나 한 중 일 언어를 모두 표시 가능합니다.

글꼴의 교체는 DATA\ART\FONTS 경로에 일반적으로 윈도우에서 사용하는 TTF 파일을 그대로 넣으시면 됩니다.
그 다음 MASTERTEXTFILE 언어파일에서 TEXT_MOD_**TO**\_FONT_A_NAME, TEXT_MOD_**TO**\_FONT_B_NAME, TEXT_MOD_**TO**\_FONT_C_NAME
이 세 항목을 위의 삽입하신 TTF파일의 영문 글꼴명을 삽입하시면 됩니다. 띄어쓰기가 있는 이름도 가능합니다.

이 세 글꼴의 원본 글꼴명은 TEXT_MOD_**FROM**\_FONT_A_NAME, TEXT_MOD_**FROM**\_FONT_B_NAME, TEXT_MOD_**FROM**\_FONT_C_NAME 에 적혀있습니다.
각각 RussellSquare, RA_Orbitron, Roboto Condensed 입니다.

# 이 저장소에 관하여.
이 저장소는 제가 개인적으로 사용하는 Radialix 3 라는 툴을 이용해서 한글화를 하기위해 여러가지 설정 파일과 프로젝트 파일을 저장하기 위해 올려둔 곳입니다.
이 번역에 참여해 주시고 싶으신 분은 프로젝트 파일을 직접 수정하시거나, sheet.csv를 수정 하신 뒤 다양한 방법으로 저에게 보내주시면 됩니다.
fork 이후 pull request를 해주셔도 좋고 이슈를 여셔서 웹링크를 주셔도 좋습니다. 참여해 주신 만큼 번역이 좀 더 빨리 완성될 겁니다.
