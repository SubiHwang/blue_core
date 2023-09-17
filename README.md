# blue_core
AI 기반 청각장애인을 위한 소리 감지 시스템 개발용 repository 입니다.

👾 멤버
- 변민정(PM, 웹앱 제작)
- 김종헌(실물 제작 밑 임베디드 코드 제작)
- 변재성(웹앱 제작)
- 이혜빈(데이터 수집 및 딥 러닝)
- 황수비(데이터 수집 및 딥 러닝)

 ---
 
⚒️ Dev Environment
- GitHub
- Notion

---

✂️ Branch Convention

```
main ── develop ── feature
```
Brach name	description

main	: 배포 중인 서비스 브랜치

• 실제 서비스가 이루어지는 브랜치입니다.	
• 해당 브랜치를 기준으로 develop 브랜치가 분기됩니다.	

develop	: 작업 브랜치

• 개발, 테스트, 릴리즈 등 배포 전 단계의 기준이 되는 브랜치입니다.	
• 프로젝트의 default 브랜치입니다.	
• 해당 브랜치에서 feature 브랜치가 분기됩니다.	

feature	기능 단위 구현
• 개별 개발자가 맡은 작업을 개발하는 브랜치입니다.	
• feature/(feature-name)처럼 머릿말-꼬릿말(개발하는 기능)으로 명명합니다.	
• kebab-case 네이밍 규칙을 준수합니다.	
