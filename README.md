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

## Support

- **Issues**: https://github.com/nasodev/nasodev-marketplace/issues

## License

MIT License
