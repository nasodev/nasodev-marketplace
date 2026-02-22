# nasodev Marketplace

Claude Code plugins by nasodev.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add nasodev/nasodev-marketplace
```

## Available Plugins

### Git Workflow

**Description:** Git workflow automation with interactive scripts. Provides branch, sync, commit, push, PR, and merge commands with lint checking and safety guards.

**Categories:** Git, Workflow, Automation, DevOps

**Install:**
```bash
/plugin install git-workflow@nasodev-marketplace
```

**What you get:**
- `/git-0-check` - Git 상태 및 설정 확인
- `/git-1-branch` - 새 브랜치 생성
- `/git-2-sync` - main 브랜치 동기화
- `/git-3-commit` - 변경사항 커밋
- `/git-4-push` - Remote에 Push
- `/git-5-pr` - Pull Request 생성
- `/git-6-merge` - Main에 머지

**Features:**
- Interactive shell scripts with color output
- Multi-language lint support (Node.js, Python, Go, Rust, Java)
- Automatic stash handling
- Branch naming validation
- Commit message guidelines

**Repository:** https://github.com/nasodev/claude-git-workflow

---

### Blog Tools

**Description:** Blog content management tools. Generate header image prompts from MDX posts and apply optimized images with compression.

**Categories:** Blog, Content, Image, MDX, Next.js

**Install:**
```bash
/plugin install blog-tools@nasodev-marketplace
```

**What you get:**
- `/blog-img` - Generate AI image prompts from blog posts
- `/blog-img-apply` - Compress and apply images to blog with frontmatter update

**Features:**
- Analyze blog content (topic, keywords, tone)
- Generate English prompts for AI image generators
- Multiple style support (minimalism, pop-art, isometric, etc.)
- Image compression (JPG, 80% quality, max 1920px)
- Auto-update MDX frontmatter

**Repository:** https://github.com/nasodev/claude-blog-tools

---

### Sonar Workflow

**Description:** SonarQube 코드 이슈를 수집 → 분석 → 수정 → 검증 → 승인까지 자동 처리하는 워크플로우 플러그인. AI 에이전트가 병렬로 이슈를 분석/수정하고, 리뷰 게이트와 TDD 게이팅을 통해 품질을 보장합니다.

**Categories:** SonarQube, Code Quality, Workflow, Automation, Jira, TDD

**Install:**
```bash
/plugin install sonar@nasodev-marketplace
```

**What you get:**
- `/sonar-setup` - 프로젝트 초기 설정 (리포 클론, 이슈 수집)
- `/sonar --action=run` - 이슈 자동 처리 (분석 → 리뷰 → 수정 → 검증)
- `/sonar --action=group` - 단순 이슈 자동 그룹화
- `/sonar --action=approve` - 승인 (Jira 생성 + 커밋 + 머지)
- `/sonar --action=status` - 워크플로우 상태 확인
- `/sonar-sync` - 웹 서비스 동기화

**Features:**
- Parallel subagent processing (max 10 concurrent)
- AI-powered code analysis and automated fixes
- Review gates with PASS/FAIL verdict (max 4 retries)
- TDD gating for BUG/VULNERABILITY issues
- Automatic issue grouping for simple patterns
- Jira ticket creation + git branch/commit/merge
- Web dashboard sync (FastAPI + Next.js)
- Git worktree isolation per issue

**Repository:** https://github.com/nasodev/claude-sonarcube-workflow

---

## Support

- **Issues**: https://github.com/nasodev/nasodev-marketplace/issues

## License

MIT License
