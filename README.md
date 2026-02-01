<div align="center">

# 🎯 Skills Warehouse

### AI 에이전트를 위한 스킬 컬렉션

[![GitHub stars](https://img.shields.io/github/stars/saykim/skills-warehouse?style=for-the-badge&logo=github&color=yellow)](https://github.com/saykim/skills-warehouse/stargazers)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=for-the-badge)](LICENSE.txt)
[![Skills](https://img.shields.io/badge/Skills-645+-purple?style=for-the-badge&logo=rocket)](.)

---

**Claude, Gemini 등 AI 에이전트의 능력을 확장하는 600개 이상의 스킬 모음**

</div>

## ✨ 특징

- 🚀 **600개 이상의 스킬** - 개발, 보안, 디자인, 마케팅 등 다양한 분야
- 📦 **즉시 사용 가능** - 각 스킬은 독립적으로 동작
- 🔧 **쉬운 커스터마이징** - 필요에 맞게 수정 가능
- 📚 **풍부한 문서화** - 각 스킬에 상세한 SKILL.md 포함

## 📁 스킬 카테고리

| 카테고리 | 설명 | 예시 |
|---------|------|------|
| 🛠️ **개발** | 프로그래밍 언어 및 프레임워크 | `python-pro`, `react-patterns`, `nextjs-best-practices` |
| 🔒 **보안** | 보안 감사 및 침투 테스트 | `security-auditor`, `pentest-checklist`, `vulnerability-scanner` |
| 🎨 **디자인** | UI/UX 및 웹 디자인 | `ui-ux-pro-max`, `web-design-guidelines`, `tailwind-patterns` |
| 📊 **데이터** | 데이터 엔지니어링 및 분석 | `data-engineer`, `sql-optimization-patterns`, `dbt-transformation-patterns` |
| ☁️ **인프라** | 클라우드 및 DevOps | `kubernetes-architect`, `terraform-specialist`, `docker-expert` |
| 🤖 **AI/ML** | 머신러닝 및 AI 개발 | `rag-engineer`, `llm-app-patterns`, `prompt-engineering` |
| 📝 **문서화** | 문서 및 콘텐츠 작성 | `api-documenter`, `writing-skills`, `copywriting` |
| 🎮 **게임** | 게임 개발 | `game-development`, `unity-developer`, `godot-gdscript-patterns` |

## 🚀 시작하기

### Claude에서 사용하기

```bash
# 원하는 스킬 폴더를 .claude/skills 디렉토리에 복사
cp -r skills-warehouse/python-pro ~/.claude/skills/

# 또는 심볼릭 링크 생성
ln -s $(pwd)/skills-warehouse/python-pro ~/.claude/skills/python-pro
```

### 스킬 구조

각 스킬은 다음 구조를 따릅니다:

```
skill-name/
├── SKILL.md          # 스킬 정의 및 지침
├── examples/         # 예제 코드 (선택)
├── scripts/          # 유틸리티 스크립트 (선택)
└── resources/        # 추가 리소스 (선택)
```

## 🌟 인기 스킬

<table>
<tr>
<td width="50%">

### 🐍 Python Pro
고급 Python 개발 패턴 및 모범 사례

</td>
<td width="50%">

### ⚛️ React Best Practices
React 성능 최적화 및 아키텍처 가이드

</td>
</tr>
<tr>
<td width="50%">

### 🔐 Security Auditor
종합적인 보안 감사 체크리스트

</td>
<td width="50%">

### 📊 PostgreSQL Best Practices
PostgreSQL 최적화 및 운영 가이드

</td>
</tr>
</table>

## 🤝 기여하기

새로운 스킬을 추가하거나 기존 스킬을 개선하고 싶다면:

1. 이 저장소를 Fork 하세요
2. 새로운 스킬 폴더를 생성하세요
3. `SKILL.md` 파일을 작성하세요
4. Pull Request를 제출하세요

## 📄 라이선스

이 프로젝트는 Apache 2.0 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE.txt](LICENSE.txt)를 참조하세요.

---

<div align="center">

**Made with ❤️ by [saykim](https://github.com/saykim)**

</div>
