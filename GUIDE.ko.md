# 한국어로 영화 시나리오를 쓰는 도구

처음 쓰는 단편이라면 **한국어 메뉴가 있는 작성 앱 하나**를 골라 장면 세 개를 써보세요. 원고가 생기면 AI에 장면의 목적과 인물의 선택을 물어볼 수 있습니다. 이미 쓰던 앱이 있다면 편집기를 바꿀 필요 없이 그 원고에 검토 방법만 적용하면 됩니다.

**편집기**는 장면 제목·지문·인물·대사의 양식을 잡습니다. **스킬**은 AI가 반복해서 따라 할 검토 절차가 담긴 파일입니다. **MCP**는 AI에 대본 검색 같은 기능을 연결하는 방식입니다. **Fountain**은 시나리오를 일반 텍스트로 저장하는 형식이며, **FDX**는 Final Draft 파일 형식입니다. PDF는 읽고 공유할 때, Fountain과 FDX는 계속 고칠 때 편합니다. [Fountain 문법](https://fountain.io/syntax/) · [Agent Skills 형식](https://agentskills.io/specification)

## 편집기와 협업 도구

| 도구 | 언제 쓰면 좋은가 | 한국어 사용법과 링크 |
|---|---|---|
| **Scenaloom** | 첫 단편을 브라우저에서 씁니다. 빈 줄에서 Tab을 눌러 인물 요소를 선택하고 ‘지연’이라고 입력하면 대사 줄로 이어집니다. | 공식 문서에 한국어 메뉴와 한국어 대본 형식이 안내돼 있습니다. PDF·DOCX·FDX·Fountain을 내보낼 수 있습니다. [한국어 사용법](https://scenaloom.com/ko/features/screenplay-editor) |
| **WriterDuet** | 공동 작가가 같은 대본을 열고 “여기서 지연이 열쇠를 숨기는 이유가 필요해”라고 장면에 댓글을 답니다. | `Customize → Interface Language → 한국어`로 메뉴를, 문서 언어에서 한국어 맞춤법을 각각 설정합니다. 유료 ReadAloud의 한국어 음성은 별도 확인이 필요합니다. [메뉴](https://www.writerduet.com/article/182-change-display-language) · [맞춤법](https://www.writerduet.com/article/249-change-document-language) · [낭독](https://www.writerduet.com/article/119-readaloud) |
| **Beat** | 맥에서 혼자 쓰면서 장면 카드로 순서를 바꾸고, 같은 Fountain 파일을 AI로 읽어봅니다. | macOS판 무료. 한국어 메뉴는 확인되지 않았습니다. 한국어 장면과 인물에 `.병원 복도 - 밤`, `@지연` 같은 Fountain 표기를 쓰고 PDF 한 페이지를 먼저 확인하세요. [Beat](https://www.beat-app.fi/) · [앱 언어](https://apps.apple.com/kr/app/beat/id1549538329?mt=12) |
| **Better Fountain** | 이미 VS Code를 쓰는 사람이 편집기 안에서 원고와 PDF 미리보기를 나란히 봅니다. | 확장 명령은 영어입니다. `Font:`에 컴퓨터에 설치한 한글 지원 글꼴을 지정하고 PDF를 미리 봅니다. [확장과 글꼴 설정](https://github.com/piersdeseilligny/betterfountain) |
| **OpenDraft** | 맥·윈도우·리눅스에서 비트 보드로 장면을 배치하고, 인물별 대사를 소리 내 들어봅니다. | 원본에 한국어 메뉴는 없습니다. 공식 문서상 첫 한국어 PDF 출력 때 CJK 글꼴을 내려받습니다. `Tools → Table Read`의 기기 음성은 운영체제에서 제공하는 음성에 따릅니다. [PDF](https://proteus-technologies-private-limited.github.io/OpenDraft/user-manual/import-export.html) · [낭독](https://proteus-technologies-private-limited.github.io/OpenDraft/user-manual/table-read.html) |
| **Arc Studio** | ‘지연이 비밀을 털어놓는다’라는 사건 카드를 실제 원고 장면과 연결해 순서를 바꿉니다. | iOS 앱 목록에는 영어가 표시됩니다. PDF 고급 설정의 `Font → Noto CJK`를 확인하세요. [플롯 보드](https://help.arcstudiopro.com/guides/the-plot-board) · [PDF 글꼴](https://help.arcstudiopro.com/how-tos/document-script-management/how-do-i-change-the-font) |
| **Fade In** | 장편을 작성하고 제작팀에 FDX를 넘깁니다. 장면을 소리 내 읽으며 호흡을 점검할 수도 있습니다. | Mac App Store판은 영어 메뉴입니다. 한글 지원 글꼴을 고르고, 내장 PDF 출력에 문제가 있으면 시스템 인쇄에서 PDF로 저장하는 방법을 제작사가 안내합니다. [도움말](https://www.fadeinpro.com/kb/overview.html) |
| **Highland Pro** | 맥과 아이패드에서 글을 쓰고, 지운 대사를 Shelf에 보관합니다. | App Store 기준 영어 메뉴입니다. 한글 PDF 조판은 이번에 확인하지 못했습니다. [제품 안내](https://quoteunquoteapps.com/highland-pro) · [앱 언어](https://apps.apple.com/kr/app/highland-pro/id6612007609) |
| **Final Draft** | 제작사나 공동 작가가 FDX를 요청하거나, 그 파일의 조판과 수정 이력을 맞춰야 할 때 씁니다. | 메뉴는 영어입니다. 한글 원고에는 기본 제공하는 `Sans Mono CJK Final Draft` 글꼴을 권합니다. [한글 글꼴](https://kb.finaldraft.com/hc/en-us/articles/15575374290964-What-foreign-languages-can-I-use-in-Final-Draft) · [화면 언어](https://kb.finaldraft.com/hc/en-us/articles/32713746186260-Can-I-change-the-Final-Draft-menus-or-UI-to-French-Spanish-Chinese-another-language) |
| **Scriptation** | 촬영 대본 PDF에 메모를 달고, 다음 수정본이 오면 기존 메모를 옮깁니다. | 공식 화면 언어 목록에 한국어가 없습니다. 한글 PDF의 메모 이동은 사본으로 확인하세요. [기능](https://scriptation.com/) · [화면 언어](https://help.scriptation.com/en/article/what-languages-is-scriptation-available-in-1nvt8u0/) |

## AI 스킬과 원고 검토

| 도구 | 언제 쓰면 좋은가 | 한국어 사용법과 링크 |
|---|---|---|
| **Screenwriting Skills 한국어판** | 단편 장면이 제자리걸음처럼 느껴질 때 “지연의 선택이 다음 장면을 바꾸는지 근거를 들어 알려줘”라고 요청합니다. | 이 저장소에 장면, 대사, 구조, 인물, 로그라인, 시리즈 설정집 스킬 여섯 개가 있습니다. Codex·Claude Code에서 쓰거나 채팅에 필요한 스킬 하나를 붙여 사용합니다. [설치와 예시](README.md) · [원본 한국어 안내](https://github.com/jtydhr88/screenwriting-skills/blob/main/README_KO.md) |
| **Story Skills** | 연재 중에 죽은 인물이 현재 시점에 다시 나오는 등 설정 충돌을 찾습니다. | 프로젝트 언어를 `ko`로 설정합니다. 한국어 결과물 라벨과 설정 검사를 지원하며, 한국어 사전에 의존하는 일부 문체 검사는 건너뜁니다. [언어 설정](https://github.com/danjdewhurst/story-skills/blob/main/docs/languages.md) |
| **filmstack Script Doctor** | 첫 초고에서 주인공이 오래 사라지는 구간을 찾고, 그게 의도인지 먼저 물어봅니다. | 원본의 재배포 라이선스를 확인하지 못했습니다. 아래 한국어 검토 프롬프트는 별도로 작성했습니다. [원본](https://github.com/vincertp/filmstack/blob/main/skills/script-doctor/SKILL.md) |
| **소설 각색 스킬 한국어판** | 내가 쓴 소설을 장편 영화로 각색합니다. 인물 둘을 합칠지 선택하고, 각 장면에 원작 장 번호를 남깁니다. | 한국어 스킬과 Fountain 표기 예시를 제공합니다. 한국어 PDF는 한글 글꼴이 필요합니다. [한국어판 포크 안내](https://github.com/H13m0n/adapting-novels-to-screenplays/blob/ko/README.ko.md) |
| **ChatGPT 프로젝트** | 설치 없이 첫 초고를 검토합니다. 인물 설정과 장면표를 올려두고 매번 같은 기준으로 질문합니다. | 한국어 메뉴를 지원합니다. 아래 검토 프롬프트를 프로젝트 지침에 넣어 반복해서 쓸 수 있습니다. [프로젝트](https://help.openai.com/en/articles/10169521-projects-in-chatgpt) · [한국어 설정](https://help.openai.com/ko-kr/articles/8357869-how-to-change-your-language-setting-in-chatgpt) |
| **Claude Projects** | 작품별 자료를 모아 두고, 1화와 2화에서 같은 단서가 어떻게 다뤄지는지 비교합니다. | 한국어 인터페이스를 지원합니다. 여러 채팅에서 공통으로 쓸 자료는 프로젝트 지식에 올립니다. [프로젝트 설정](https://support.anthropic.com/en/articles/9519177-how-can-i-create-and-manage-projects) · [한국어 설정](https://support.claude.com/en/articles/10769299-how-to-use-claude-in-your-preferred-language) |
| **ScriptRAG** | 여러 회차에서 “형사가 피해자의 이름을 처음 들은 장면은 어디인가?”를 검색합니다. | Fountain을 색인하는 MCP입니다. 한글 이름과 장면 표기가 실제 검색에서 잘 잡히는지는 짧은 샘플로 확인하세요. 한두 장면만 검토할 때는 파일을 AI에 바로 보여주는 방법이 간단합니다. [설치와 MCP 예제](https://github.com/trieloff/scriptrag) |
| **Greenlight Coverage** | 완성된 초고를 외부 독자에게 주기 전 구조와 속도에 대한 검토 보고서를 받아봅니다. | 공급사는 한국어 대본을 받으며 보고서는 영어로 제공한다고 안내합니다. “장면 번호와 고유명사를 유지하고 이 보고서를 한국어로 옮겨줘”라고 요청해 읽을 수 있습니다. [언어 안내](https://glcoverage.com/blog/ai-script-coverage-international-writers/) · [보고서 샘플](https://glcoverage.com/sample-analysis/) |
| **FinalBit** | 초고에서 장소·등장인물·소품을 뽑아 제작 준비 목록을 만듭니다. | 공식 안내에서 한국어 지원을 확인하지 못했습니다. 꼭 필요하다면 원고 한 장의 영문 요약으로 시험해보고 결과를 한국어로 옮기는 방법이 있습니다. [기능 안내](https://www.finalbitai.com/) |
| **Novelcrafter** | 장편 소설의 인물과 세계관을 관리하며 “지연이 운전을 피하는 이유가 앞부분과 맞는지” 확인합니다. | 작품 언어는 화면 언어와 별개입니다. 한국어로 쓰고 검토할 수 있는 연결 모델을 선택합니다. [작품 언어](https://www.novelcrafter.com/courses/ultimate-beginners-guide/create-novel) · [설정집](https://www.novelcrafter.com/features/codex) |
| **Inkwell** | 설치형 도구로 소설을 쓰고, 로컬 모델에 한 장의 퇴고를 맡깁니다. | 공개 소스의 화면은 영어입니다. 모델의 한국어 품질과 한글 내보내기는 한 장으로 먼저 확인하세요. [로컬 모델 안내](https://github.com/joshuaopel/inkwell) |

### 그대로 붙여 쓸 장면 검토 프롬프트

> 내가 쓴 한국어 영화 시나리오의 이 장면을 검토해줘. 인물별로 원하는 것, 그걸 얻기 위해 실제로 한 행동, 장면 끝에 달라진 것을 짧게 적어줘. 문제가 보이면 ‘원고에서 확인한 사실’, ‘가능한 해석’, ‘내가 결정할 질문’을 나눠서 써줘. 근거에 장면 번호나 해당 대사를 붙여줘. 수정 제안은 한두 개면 충분해. 내가 선택하기 전에는 원고를 고치지 마.

### 작법을 익히거나 실제 제작 흐름을 볼 때

- **존 어거스트의 공개 대본과 작법 글.** 먼저 장면 하나를 읽고, 빠지면 이야기에서 무엇이 사라지는지 생각해 봅니다. 공개 대본은 페이지 구성과 대사 리듬을 비교하는 데도 쓸 수 있습니다. [장면 쓰기](https://johnaugust.com/2007/write-scene) · [공개 대본](https://johnaugust.com/library) · [첫 3쪽 피드백](https://johnaugust.com/threepage)
- **《더 라스트 오브 어스》.** 크레이그 메이진은 Fade In으로 집필하고, 제작팀은 배포에 Scenechronize를 쓰며, 현장 도구 호환을 위해 Final Draft 파일로 변환한다고 설명했습니다. 같은 회차에서 존 어거스트는 Highland를 쓴다고 밝혔습니다. [Scriptnotes 646화](https://johnaugust.com/2024/scriptnotes-episode-646-industry-software-transcript)
- **Dramatron과 Runway.** Dramatron은 영화·연극 종사자와 진행한 시나리오 공동 집필 연구입니다. Lionsgate와 Runway가 공개한 협업 범위는 프리비즈·스토리보드·영상 제작입니다. [Dramatron 연구](https://deepmind.google/research/publications/13609/) · [Lionsgate 발표](https://runway.com/news/company-news/runway-and-lionsgate-expand-partnership)

국내 공모에 낸다면 원고를 정리한 뒤 그 공모의 제출 양식을 적용하세요. 영진위는 공고에 신청 양식과 접수 가이드를 첨부합니다. 표의 앱별 언어 지원은 2026년 11월 10일 기준 공식 안내와 소스에 근거하며, 낭독·PDF 항목의 확인 범위는 각 행에 표시했습니다. [영화진흥위원회 공고 예시](https://www.kofic.kr/kofic/business/prom/promotionBoardDetail.do?seqNo=17692)
