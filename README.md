# 영화·드라마 작법 스킬 한국어판

스킬은 Codex나 Claude Code가 특정 작업을 할 때 읽는 **작업 안내서**입니다. 예를 들어 장면 스킬을 쓰면 AI가 장면의 목적, 인물의 선택, 그 선택이 다음 장면에 미치는 영향을 순서대로 살핍니다. 원고는 평소 쓰던 편집기에서 작성하고, 검토를 받고 싶은 부분을 AI에 보여주면 됩니다.

처음이라면 **[시나리오 도구별 한국어 가이드](GUIDE.ko.md)**에서 작성 앱과 검토 방법을 먼저 고르세요. 설치 없이 쓸 수 있는 검토 프롬프트도 있습니다.

| 스킬 | 써볼 상황 | 요청 예시 |
|---|---|---|
| [아이디어와 주제](skills/sw-premise-theme/SKILL.md) | 떠오른 아이디어를 영화 한 편으로 발전시킬 때 | “주인공이 무엇을 원하고, 실패하면 무엇을 잃는지 드러나는 로그라인을 만들어줘.” |
| [이야기 구조](skills/sw-story-structure/SKILL.md) | 중반이 늘어지거나 결말이 뜬금없을 때 | “장면 목록에서 주인공의 선택이 다음 사건으로 이어지지 않는 곳을 짚어줘.” |
| [인물과 갈등](skills/sw-character-conflict/SKILL.md) | 인물들이 왜 서로 부딪히는지 약할 때 | “두 사람이 같은 보증금을 원하는 이유를 다르게 잡고, 한 사람이 양보하면 잃는 걸 정리해줘.” |
| [장면 쓰기와 검토](skills/sw-scene-craft/SKILL.md) | 장면은 있는데 달라지는 게 없어 보일 때 | “이 장면을 빼면 다음 장면에서 무엇이 이해되지 않는지 알려줘.” |
| [대사와 서브텍스트](skills/sw-dialogue/SKILL.md) | 대사가 설명처럼 들리거나 말투가 비슷할 때 | “인물 이름을 지우면 누가 말했는지 헷갈리는 줄을 골라줘.” |
| [시리즈 설정집](skills/sw-series-engine-bible/SKILL.md) | 파일럿 이후에도 이야기가 나올지 점검할 때 | “이 설정으로 2~4화에서 벌어질 서로 다른 갈등을 짧게 보여줘.” |

## 프로젝트에 넣기

아래 명령을 **원고 프로젝트 폴더**에서 실행합니다. 이미 같은 이름의 스킬을 설치했다면 먼저 어느 판을 쓸지 정하세요.

```bash
git clone https://github.com/H13m0n/screenwriting-skills-ko.git
mkdir -p .agents/skills
cp -R screenwriting-skills-ko/skills/sw-scene-craft .agents/skills/
```

위 예시는 **Codex**에서 장면 스킬 하나만 설치합니다. 프로젝트를 열고 `$sw-scene-craft`를 선택해 “`script.fountain`의 3번 장면을 검토하고, 수정은 하지 말고 근거와 선택지만 보여줘”라고 요청할 수 있습니다. **Claude Code**라면 위 두 명령의 `.agents/skills`를 `.claude/skills`로 바꿔 복사한 뒤 `/sw-scene-craft`를 사용합니다. 설치가 부담스러우면 이 저장소에서 스킬 하나를 열어 그 내용을 쓰던 AI 채팅에 붙여도 됩니다.

[Agent Skills 형식](https://agentskills.io/specification) · [Codex 스킬 안내](https://developers.openai.com/codex/skills) · [Claude Code 스킬 안내](https://code.claude.com/docs/en/skills)

## 출처와 라이선스

원본은 jtydhr88의 [screenwriting-skills](https://github.com/jtydhr88/screenwriting-skills)이며 기준 리비전은 [51115f1](https://github.com/jtydhr88/screenwriting-skills/commit/51115f18d160aa8b2ac5813e4432b0b425358f)입니다. 원본의 작법 원칙과 체크리스트를 바탕으로 여섯 가지 핵심 스킬을 한국어로 재구성했습니다. 한국어판의 예시는 새로 작성했습니다.

원본 [NOTICE](https://github.com/jtydhr88/screenwriting-skills/blob/51115f18d160aa8b2ac5813e4432b0b425358f/NOTICE)는 제3자 책·대본의 인용문과 번역문을 MIT 허가 범위에서 제외합니다. 이 저장소는 원본 Git 이력이나 해당 자료를 포함하지 않으며, 원본 저작권 표시를 담은 [MIT 라이선스](LICENSE)를 따릅니다. 전체 26개 스킬은 [원본 한국어 안내](https://github.com/jtydhr88/screenwriting-skills/blob/main/README_KO.md)에서 볼 수 있습니다.
