# Danh Mục Skills — Claude Code
> Cập nhật: 2026-03-27 | Tổng cộng: ~1,740+ skills từ 7 marketplaces

---

## Tổng Quan

| Nguồn | Số Skills | Phiên bản | Mô tả |
|-------|-----------|-----------|-------|
| [Built-in Commands](#1-built-in-commands) | ~88 | latest | Lệnh gốc tích hợp sẵn |
| [skills/* (Built-in)](#2-skills-built-in) | 125 | latest | Skills chuyên sâu tích hợp |
| [antigravity-awesome-skills](#3-antigravity-awesome-skills) | 1,319 | 7.7.0 | Thư viện cộng đồng lớn nhất |
| [claude-scientific-writer](#4-claude-scientific-writer) | 24 | 0.1.0 | Viết khoa học & y tế |
| [claude-scientific-skills](#5-claude-scientific-skills) | 177 | latest | Công cụ khoa học chuyên sâu |
| [claude-skills (alirezarezvani)](#6-claude-skills-alirezarezvani) | 175 | 2.1.2 | Business, Engineering, C-level |
| [agency-agents](#7-agency-agents) | ~153 | latest | Agents theo domain |
| [claude-plugins-official](#8-claude-plugins-official) | 32 | latest | Plugins chính thức Anthropic |

---

## 1. Built-in Commands

Các lệnh `/` tích hợp sẵn trong Claude Code.

### Workflow & Project
| Skill | Mô tả |
|-------|-------|
| `plan` | Đánh giá rủi ro và lập kế hoạch |
| `feature-development` | Phát triển tính năng theo workflow |
| `database-migration` | Workflow migration database |
| `checkpoint` | Lưu checkpoint session |
| `save-session` / `resume-session` | Quản lý session |
| `sprint-plan` / `sprint-health` | Agile sprint management |
| `retro` | Retrospective |
| `okr` | OKR tracking |
| `prd` / `user-story` / `code-to-prd` | Product requirements |
| `project-health` / `saas-health` / `financial-health` | Health checks |
| `rice` | RICE prioritization |

### Code Quality & Review
| Skill | Mô tả |
|-------|-------|
| `code-review` | Review code tổng quát |
| `simplify` | Tối ưu code đã thay đổi |
| `refactor-clean` | Refactor sạch |
| `security-scan` | Quét bảo mật |
| `tdd` | Test-driven development |
| `quality-gate` | Kiểm tra chất lượng |
| `verify` | Xác minh build/test |
| `focused-fix` | Sửa lỗi tập trung |
| `build-fix` | Sửa lỗi build |
| `review` | Review gate trước khi push |
| `test-coverage` | Độ phủ test |

### Language-Specific
| Skill | Mô tả |
|-------|-------|
| `go-build` / `go-review` / `go-test` | Go language |
| `python-review` | Python review |
| `rust-build` / `rust-review` / `rust-test` | Rust language |
| `cpp-build` / `cpp-review` / `cpp-test` | C++ language |
| `kotlin-build` / `kotlin-review` / `kotlin-test` | Kotlin language |
| `gradle-build` | Gradle build |

### AI & Multi-Agent
| Skill | Mô tả |
|-------|-------|
| `devfleet` | Orchestrate nhiều agent song song |
| `orchestrate` | Sequential & tmux orchestration |
| `multi-plan` / `multi-execute` / `multi-workflow` | Multi-model collaboration |
| `multi-backend` / `multi-frontend` | Chuyên biệt theo tầng |
| `model-route` | Định tuyến model |
| `pipeline` | Pipeline workflow |
| `persona` | Persona switching |
| `claw` | NanoClaw REPL |

### Git & Version Control
| Skill | Mô tả |
|-------|-------|
| `git:cm` | Stage + commit |
| `git:cp` | Stage + commit + push |
| `git:pr` | Tạo pull request |
| `git:clean` | Dọn branch đã merge |
| `changelog` | Tạo changelog |

### Research & Documentation
| Skill | Mô tả |
|-------|-------|
| `docs` | Lookup tài liệu thư viện |
| `seo-auditor` | SEO audit docs |
| `update-docs` | Cập nhật documentation |
| `update-codemaps` | Cập nhật code maps |
| `context-budget` | Phân tích context window |

### Skills Management
| Skill | Mô tả |
|-------|-------|
| `skill-create` | Tạo skill từ git history |
| `skill-health` | Dashboard tình trạng skills |
| `plugin-audit` | Audit pipeline cho skills |
| `instinct-status` / `instinct-import` / `instinct-export` | Quản lý instincts |
| `evolve` | Phân tích và cải tiến instincts |
| `learn` / `learn-eval` | Extract patterns |
| `promote` / `prune` | Quản lý instinct lifecycle |
| `rules-distill` | Trích xuất nguyên tắc từ skills |
| `harness-audit` | Audit harness |
| `projects` / `sessions` | Quản lý projects/sessions |

### Productivity
| Skill | Mô tả |
|-------|-------|
| `loop-start` / `loop-status` | Recurring tasks |
| `aside` | Câu hỏi nhanh không làm gián đoạn |
| `competitive-matrix` | Ma trận cạnh tranh |
| `google-workspace` | Google Workspace CLI |
| `pm2` | PM2 process manager |
| `eval` | Evaluation |
| `prompt-optimize` | Tối ưu prompt |
| `tech-debt` | Tracking tech debt |
| `setup-pm` | Cài đặt PM tools |

---

## 2. Skills Built-in

Skills chuyên sâu tích hợp sẵn (gọi với prefix `skills:`).

### AI & Agent Engineering
| Skill | Mô tả |
|-------|-------|
| `skills:autonomous-loops` | Patterns cho agent tự động |
| `skills:continuous-agent-loop` | Agent loop liên tục |
| `skills:claude-devfleet` | Multi-agent orchestration |
| `skills:dmux-workflows` | tmux multi-agent |
| `skills:eval-harness` | Formal evaluation framework |
| `skills:agent-eval` | Head-to-head agent comparison |
| `skills:agent-harness-construction` | Agent action space design |
| `skills:agentic-engineering` | Agentic engineering ops |
| `skills:ai-first-engineering` | AI-first engineering model |
| `skills:ai-regression-testing` | AI regression testing |
| `skills:team-builder` | Agent team composer |
| `skills:santa-method` | Multi-agent adversarial verification |
| `skills:ralphinho-rfc-pipeline` | RFC-driven DAG execution |
| `skills:enterprise-agent-ops` | Long-lived agent workloads |
| `skills:continuous-learning` / `skills:continuous-learning-v2` | Tự học từ session |
| `skills:strategic-compact` | Context compaction |

### Backend & Database
| Skill | Mô tả |
|-------|-------|
| `skills:backend-patterns` | Backend architecture |
| `skills:database-migrations` | Schema migration patterns |
| `skills:postgres-patterns` | PostgreSQL patterns |
| `skills:clickhouse-io` | ClickHouse patterns |
| `skills:jpa-patterns` | JPA/Hibernate |
| `skills:springboot-patterns` / `skills:springboot-security` / `skills:springboot-tdd` / `skills:springboot-verification` | Spring Boot |
| `skills:django-patterns` / `skills:django-security` / `skills:django-tdd` / `skills:django-verification` | Django |
| `skills:laravel-patterns` / `skills:laravel-security` / `skills:laravel-tdd` / `skills:laravel-verification` | Laravel |

### Frontend & Mobile
| Skill | Mô tả |
|-------|-------|
| `skills:frontend-patterns` | Frontend React/Vue/etc |
| `skills:swiftui-patterns` | SwiftUI patterns |
| `skills:swift-concurrency-6-2` | Swift 6.2 concurrency |
| `skills:swift-actor-persistence` | Swift actor persistence |
| `skills:swift-protocol-di-testing` | Swift DI testing |
| `skills:android-clean-architecture` | Android clean arch |
| `skills:compose-multiplatform-patterns` | Compose Multiplatform |
| `skills:kotlin-patterns` / `skills:kotlin-testing` / `skills:kotlin-coroutines-flows` / `skills:kotlin-ktor-patterns` / `skills:kotlin-exposed-patterns` | Kotlin |
| `skills:nuxt4-patterns` | Nuxt 4 |
| `skills:nextjs-turbopack` | Next.js 16+ Turbopack |
| `skills:bun-runtime` | Bun runtime |
| `skills:liquid-glass-design` | iOS 26 Liquid Glass design |
| `skills:foundation-models-on-device` | Apple FoundationModels |
| `skills:frontend-slides` | HTML presentation |
| `skills:flutter-dart-code-review` | Flutter/Dart review |

### DevOps & Infrastructure
| Skill | Mô tả |
|-------|-------|
| `skills:docker-patterns` | Docker/Compose |
| `skills:deployment-patterns` | CI/CD patterns |
| `skills:mcp-server-patterns` | MCP server với Node/TS |
| `skills:cost-aware-llm-pipeline` | LLM cost optimization |
| `skills:canary-watch` | Post-deploy monitoring |

### Languages & Testing
| Skill | Mô tả |
|-------|-------|
| `skills:golang-patterns` / `skills:golang-testing` | Go |
| `skills:python-patterns` / `skills:python-testing` | Python |
| `skills:rust-patterns` / `skills:rust-testing` | Rust |
| `skills:cpp-coding-standards` / `skills:cpp-testing` | C++ |
| `skills:java-coding-standards` | Java |
| `skills:perl-patterns` / `skills:perl-security` / `skills:perl-testing` | Perl |
| `skills:pytorch-patterns` | PyTorch |
| `skills:e2e-testing` | Playwright E2E |
| `skills:browser-qa` | Visual browser testing |
| `skills:tdd-workflow` | TDD workflow |

### Research & Content
| Skill | Mô tả |
|-------|-------|
| `skills:deep-research` | Multi-source research |
| `skills:search-first` | Research trước khi code |
| `skills:article-writing` | Viết bài |
| `skills:content-engine` | Content system |
| `skills:crosspost` | Multi-platform distribution |
| `skills:market-research` | Market research |
| `skills:documentation-lookup` | Tra cứu docs |
| `skills:exa-search` | Neural search via Exa |
| `skills:iterative-retrieval` | Progressive context retrieval |

### Security
| Skill | Mô tả |
|-------|-------|
| `skills:security-review` | Security review |
| `skills:security-scan` | Scan Claude config |
| `skills:safety-guard` | Prevent destructive ops |
| `skills:django-security` / `skills:laravel-security` / `skills:springboot-security` / `skills:perl-security` | Framework security |

### Specialized
| Skill | Mô tả |
|-------|-------|
| `skills:claude-api` | Claude API patterns |
| `skills:x-api` | X/Twitter API |
| `skills:fal-ai-media` | Media generation via fal.ai |
| `skills:videodb` | Video/audio understanding |
| `skills:video-editing` | AI video editing |
| `skills:visa-doc-translate` | Visa document translation |
| `skills:nutrient-document-processing` | Document OCR/extract |
| `skills:carrier-relationship-management` | Carrier management |
| `skills:customs-trade-compliance` | Customs compliance |
| `skills:energy-procurement` | Energy procurement |
| `skills:logistics-exception-management` | Freight exception mgmt |
| `skills:inventory-demand-planning` | Demand planning |
| `skills:production-scheduling` | Production scheduling |
| `skills:quality-nonconformance` | Quality control |
| `skills:returns-reverse-logistics` | Returns logistics |
| `skills:investor-materials` | Pitch decks |
| `skills:investor-outreach` | Cold email investors |
| `skills:nanoclaw-repl` | NanoClaw REPL |
| `skills:blueprint` | One-line → step-by-step plan |
| `skills:product-lens` | Product thinking |
| `skills:skill-comply` | Skill/rule compliance |
| `skills:skill-stocktake` | Skill audit |
| `skills:regex-vs-llm-structured-text` | Regex vs LLM decision |
| `skills:content-hash-cache-pattern` | Cache file processing |
| `skills:coding-standards` | Universal coding standards |
| `skills:api-design` | REST API design |
| `skills:architecture-decision-records` | ADR capture |
| `skills:codebase-onboarding` | Codebase analysis |
| `skills:benchmark` | Performance baseline |
| `skills:click-path-audit` | User journey audit |
| `skills:design-system` | Design system audit |
| `skills:plankton-code-quality` | Write-time quality |
| `skills:verification-loop` | Comprehensive verification |
| `skills:data-scraper-agent` | AI data scraping |
| `skills:configure-ecc` | ECC installer |
| `skills:project-guidelines-example` | Project skill template |
| `skills:prompt-optimizer` | Prompt optimization |
| `skills:rules-distill` | Extract principles |

---

## 3. antigravity-awesome-skills

**1,319 skills** từ cộng đồng — thư viện lớn nhất. Phiên bản **7.7.0**.
Repo: [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills)

### Danh mục nổi bật
| Nhóm | Ví dụ Skills |
|------|-------------|
| **Security** | `007`, `active-directory-attacks`, `aegisops-ai`, `zeroize-audit`, `windows-privilege-escalation`, `xss-html-injection`, `wordpress-penetration-testing` |
| **AI & Agents** | `agent-orchestrator`, `agent-memory-systems`, `ai-engineer`, `ai-agents-architect`, `agentic-actions-auditor`, `agenthub`, `agentfolio` |
| **Cloud & DevOps** | `airflow-dag-patterns`, `algorithmic-art`, `workflow-automation`, `workflow-orchestration-patterns` |
| **Automation** | `activecampaign-automation`, `airtable-automation`, `whatsapp-automation`, `zapier-make-patterns`, `zendesk-automation`, `zoom-automation`, `zoho-crm-automation` |
| **Marketing** | `ad-creative`, `ai-seo`, `x-article-publisher-skill`, `youtube-automation`, `youtube-summarizer` |
| **Legal** | `advogado-criminal`, `advogado-especialista` |
| **Document** | `xlsx`, `xlsx-official`, `wiki-architect`, `wiki-page-writer` |
| **Testing** | `webapp-testing`, `web3-testing`, `wireshark-analysis` |
| **Andruia Suite** | `00-andruia-consultant`, `10-andruia-skill-smith`, `20-andruia-niche-intelligence` |
| **Writing** | `writing-skills`, `writing-plans` |

> Xem đầy đủ tại: `~/.claude/plugins/marketplaces/antigravity-awesome-skills/skills/`

---

## 4. claude-scientific-writer

**24 skills** cho viết khoa học & y tế. Phiên bản **0.1.0**.
Repo: [K-Dense-AI/claude-scientific-writer](https://github.com/K-Dense-AI/claude-scientific-writer)

| Skill | Mô tả |
|-------|-------|
| `citation-management` | Quản lý trích dẫn, BibTeX, PubMed, DOI |
| `clinical-decision-support` | Hỗ trợ quyết định lâm sàng |
| `clinical-reports` | Báo cáo lâm sàng (HIPAA, SAE, CSR) |
| `document-skills/docx` | Tạo/chỉnh sửa file Word (OOXML) |
| `document-skills/pdf` | Xử lý PDF, form filling |
| `document-skills/pptx` | PowerPoint automation |
| `document-skills/xlsx` | Excel automation |
| `generate-image` | Tạo hình ảnh |
| `hypothesis-generation` | Sinh giả thuyết nghiên cứu |
| `infographics` | Tạo infographic khoa học |
| `latex-posters` | Poster hội nghị bằng LaTeX |
| `literature-review` | Review tài liệu khoa học |
| `market-research-reports` | Báo cáo nghiên cứu thị trường |
| `markitdown` | Chuyển đổi tài liệu sang Markdown |
| `paper-2-web` | Chuyển paper → web/video/poster |
| `parallel-web` | Web research song song |
| `peer-review` | Peer review bài báo |
| `pptx-posters` | Poster bằng PowerPoint |
| `research-grants` | Đề xuất tài trợ (NIH, NSF, DARPA) |
| `research-lookup` | Tra cứu nghiên cứu |
| `scholar-evaluation` | Đánh giá học thuật |
| `scientific-critical-thinking` | Tư duy phản biện khoa học |
| `scientific-schematics` | Sơ đồ khoa học |
| `scientific-slides` | Slide trình bày khoa học |
| `scientific-writing` | Viết bài khoa học (IMRaD) |
| `treatment-plans` | Kế hoạch điều trị y tế |
| `venue-templates` | Templates theo hội nghị/tạp chí |

---

## 5. claude-scientific-skills

**177 skills** công cụ khoa học chuyên sâu.
Repo: [K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)

### Nhóm nổi bật
| Nhóm | Skills |
|------|--------|
| **Bioinformatics** | `alphafold-database`, `biopython`, `cellxgene-census`, `anndata`, `arboreto` |
| **Chemistry** | `chembl-database`, `bindingdb-database`, `brenda-database`, `cobrapy` |
| **Clinical/Medical** | `clinicaltrials-database`, `clinpgx-database`, `clinvar-database`, `cbioportal-database` |
| **Research Databases** | `arxiv-database`, `alpha-vantage`, `biorxiv-database`, `cosmic-database` |
| **Scientific Computing** | `astropy`, `dask`, `cirq`, `adaptyv` |
| **Integration** | `benchling-integration`, `bioservices`, `bgpt-paper-search` |

> Xem đầy đủ tại: `~/.claude/plugins/marketplaces/claude-scientific-skills/scientific-skills/`

---

## 6. claude-skills (alirezarezvani)

**175 skills** production-ready, 9 domains. Phiên bản **2.1.2**.
Repo: [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)

### Marketing (43 skills)
| Skill | Mô tả |
|-------|-------|
| `content-creator` | SEO content với brand voice |
| `content-strategy` / `content-production` / `content-humanizer` | Content pipeline |
| `copywriting` / `copy-editing` | Copywriting |
| `ai-seo` / `seo-audit` / `programmatic-seo` / `schema-markup` / `site-architecture` | SEO |
| `form-cro` / `page-cro` / `onboarding-cro` / `signup-flow-cro` / `popup-cro` / `paywall-upgrade-cro` | CRO |
| `paid-ads` / `campaign-analytics` | Paid media |
| `cold-email` / `email-sequence` / `email-template-builder` | Email marketing |
| `social-media-manager` / `social-content` / `social-media-analyzer` | Social media |
| `x-twitter-growth` | X/Twitter growth |
| `marketing-strategy-pmm` / `marketing-ideas` / `marketing-context` / `marketing-ops` | Strategy |
| `competitive-intel` / `competitor-alternatives` | Intelligence |
| `brand-guidelines` / `marketing-psychology` | Brand |
| `free-tool-strategy` / `referral-program` / `launch-strategy` / `churn-prevention` | Growth |
| `app-store-optimization` | ASO |
| `internal-narrative` / `intl-expansion` | Misc |

### C-Level Advisory (28 skills)
| Skill | Mô tả |
|-------|-------|
| `ceo-advisor` / `cto-advisor` / `coo-advisor` / `cpo-advisor` / `cmo-advisor` / `cfo-advisor` / `cro-advisor` / `ciso-advisor` / `chro-advisor` | Virtual board |
| `executive-mentor` / `founder-coach` | Mentoring |
| `chief-of-staff` / `board-meeting` / `decision-logger` | Orchestration |
| `board-deck-builder` / `scenario-war-room` / `competitive-teardown` / `ma-playbook` | Strategy |
| `change-management` / `culture-architect` / `org-health-diagnostic` / `strategic-alignment` | Culture |
| `pricing-strategy` / `company-os` / `agent-protocol` | Operations |

### Engineering Advanced (35 skills)
| Skill | Mô tả |
|-------|-------|
| `agent-designer` / `agent-workflow-designer` / `agenthub` | Agent design |
| `rag-architect` / `database-designer` / `database-schema-designer` | Architecture |
| `browser-automation` / `spec-driven-workflow` | Automation |
| `secrets-vault-manager` / `env-secrets-manager` / `skill-security-auditor` | Security |
| `sql-database-assistant` / `migration-architect` | Database |
| `observability-designer` / `dependency-auditor` / `performance-profiler` | Ops |
| `release-manager` / `api-design-reviewer` / `ci-cd-pipeline-builder` | DevOps |
| `mcp-server-builder` / `docker-development` / `helm-chart-builder` / `terraform-patterns` | Infrastructure |
| `autoresearch-agent` | Autonomous research loop |
| `monorepo-navigator` / `git-worktree-manager` / `runbook-generator` | Dev tools |

### Engineering Team (30 skills)
| Skill | Mô tả |
|-------|-------|
| `senior-architect` / `senior-frontend` / `senior-backend` / `senior-fullstack` / `senior-devops` | Senior roles |
| `senior-security` / `senior-secops` / `senior-qa` / `senior-prompt-engineer` | Specialist roles |
| `senior-ml-engineer` / `senior-data-scientist` / `senior-data-engineer` / `senior-computer-vision` | AI/ML |
| `playwright-pro` (9 sub-skills) | E2E testing |
| `self-improving-agent` | Auto-memory & learning |
| `stripe-integration-expert` / `tdd-guide` / `tech-stack-evaluator` | Dev skills |
| `aws-solution-architect` / `azure-cloud-architect` / `gcp-cloud-architect` | Cloud |
| `snowflake-development` / `security-pen-testing` | Specialized |
| `google-workspace-cli` / `a11y-audit` | Tools |

### Product (14 skills)
| Skill | Mô tả |
|-------|-------|
| `product-manager-toolkit` / `agile-product-owner` / `product-strategist` | PM core |
| `ux-researcher-designer` / `ui-design-system` | Design |
| `competitive-teardown` / `landing-page-generator` | Research |
| `saas-scaffolder` / `product-analytics` / `experiment-designer` | Build |
| `product-discovery` / `roadmap-communicator` | Lifecycle |
| `code-to-prd` / `research-summarizer` | Documentation |

### Regulatory/QMS (13 skills)
| Skill | Mô tả |
|-------|-------|
| `quality-manager-qms-iso13485` / `qms-audit-expert` / `quality-manager-qmr` | ISO 13485 |
| `mdr-745-specialist` / `fda-consultant-specialist` | Medical device |
| `gdpr-dsgvo-expert` / `information-security-manager-iso27001` / `isms-audit-expert` | Privacy/Security |
| `soc2-compliance` / `risk-management-specialist` | Compliance |
| `capa-officer` / `quality-documentation-manager` / `regulatory-affairs-head` | Quality |

### Project Management (6 skills)
`senior-pm`, `scrum-master`, `jira-expert`, `confluence-expert`, `atlassian-admin`, `atlassian-templates`

### Business Growth (4 skills)
`customer-success-manager`, `sales-engineer`, `revenue-operations`, `contract-and-proposal-writer`

### Finance (2 skills)
`financial-analyst`, `saas-metrics-coach`

---

## 7. agency-agents

**~153 agent skills** theo domain.
Repo: [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)

| Domain | Số Items | Ví dụ |
|--------|----------|-------|
| `marketing` | 27 | Content, SEO, email, social |
| `engineering` | 23 | Code review, architecture, DevOps |
| `specialized` | 27 | Domain-specific agents |
| `game-development` | 10 | Game design, mechanics |
| `integrations` | 11 | API, third-party |
| `sales` | 8 | Sales process, CRM |
| `testing` | 8 | QA, automation |
| `design` | 8 | UI/UX, visual |
| `paid-media` | 7 | Ads, campaigns |
| `project-management` | 6 | PM, Agile |
| `spatial-computing` | 6 | AR/VR |
| `strategy` | 6 | Business strategy |
| `support` | 6 | Customer support |
| `product` | 5 | Product management |
| `academic` | 5 | Research, writing |

---

## 8. claude-plugins-official

**32 plugins chính thức** từ Anthropic.
Repo: [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)

| Plugin | Mô tả |
|--------|-------|
| `agent-sdk-dev` | Agent SDK development |
| `claude-code-setup` | Setup Claude Code |
| `claude-md-management` | Quản lý CLAUDE.md |
| `code-review` | Code review chính thức |
| `code-simplifier` | Đơn giản hóa code |
| `commit-commands` | Git commit workflows |
| `feature-dev` | Feature development |
| `frontend-design` | Frontend design patterns |
| `hookify` | Hook configuration |
| `mcp-server-dev` | MCP server development |
| `plugin-dev` | Plugin development |
| `pr-review-toolkit` | PR review tools |
| `ralph-loop` | Ralph loop pattern |
| `security-guidance` | Security guidance |
| `skill-creator` | Tạo skill mới |
| `learning-output-style` / `explanatory-output-style` | Output styles |
| **LSP Plugins** | `clangd-lsp`, `csharp-lsp`, `gopls-lsp`, `jdtls-lsp`, `kotlin-lsp`, `lua-lsp`, `php-lsp`, `pyright-lsp`, `ruby-lsp`, `rust-analyzer-lsp` |
| `math-olympiad` | Toán học olympiad |
| `playground` / `example-plugin` | Templates |

---

## Tóm Tắt Nhanh

```
Built-in Commands:     ~88 skills
Built-in skills/*:     125 skills
antigravity:         1,319 skills
claude-scientific-writer: 24 skills
claude-scientific-skills: 177 skills
claude-skills:          175 skills
agency-agents:          153 skills
claude-plugins-official:  32 skills
─────────────────────────────────
TỔNG CỘNG:          ~2,093 skills
```

### Strengths theo lĩnh vực

| Lĩnh vực | Mức độ |
|----------|--------|
| AI/Agent Engineering | ⭐⭐⭐⭐⭐ |
| Scientific Writing & Research | ⭐⭐⭐⭐⭐ |
| Backend & DevOps | ⭐⭐⭐⭐⭐ |
| Marketing & Growth | ⭐⭐⭐⭐⭐ |
| Security | ⭐⭐⭐⭐⭐ |
| C-Level Advisory | ⭐⭐⭐⭐ |
| Frontend & Mobile | ⭐⭐⭐⭐ |
| Compliance & Regulatory | ⭐⭐⭐⭐ |
| Finance | ⭐⭐⭐ |
| Game Development | ⭐⭐⭐ |
