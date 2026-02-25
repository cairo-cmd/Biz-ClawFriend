# -----------------------------------------------------------------------------
# DELIVERABLE 1: COMPETITIVE LANDSCAPE (25%)
# -----------------------------------------------------------------------------

[step_1]
name = Competitive Landscape
weight = 25%
reason = Biết đối thủ → biết "mình khác ở đâu" → chọn skill và kênh có căn cứ
tasks = Tìm 5–10 đối thủ Web3 skill marketplace | Mỗi đối thủ: Tên, Link, Mô tả, Số liệu (≥2), Monetization, Điểm mạnh/yếu | User chọn/không chọn vì sao | So sánh chain, pricing, gap thị trường | Kết luận: mình khác ở đâu, segment bỏ ngỏ, thắng/thua
output = competitive-landscape.md

[rubric_step_1]
criteria_1 = Chất lượng phân tích đối thủ (10đ): Nhận xét RIÊNG mỗi đối thủ — làm tốt/dở gì, user chọn/không chọn vì sao, bài học
criteria_2 = Số liệu & Data thực (6đ): Mỗi đối thủ ≥2 số liệu có nguồn (user, download, stars, pricing, GMV)
criteria_3 = So sánh & Insight (5đ): So sánh chain, pricing, gap thị trường, giai đoạn (nascent/growing/mature)
criteria_4 = Kết luận & Định vị (4đ): Marketplace khác ở đâu, segment bỏ ngỏ, lợi thế cạnh tranh

status = done

# -----------------------------------------------------------------------------
# DELIVERABLE 2: SKILL RESEARCH (25%)
# -----------------------------------------------------------------------------

[step_2]
name = Skill Research
weight = 25%
reason = Đã rõ gap thị trường → đề xuất skill bám gap, tránh trùng đối thủ
tasks = Liệt kê 5–10 skill | Mỗi skill: Tên, Target user cụ thể, Problem, Alternative hiện tại, Skill giải quyết thế nào | Visibility & Monetization (Public/Private, holder-gated, số shares) | Bằng chứng demand (search volume, forum, Twitter, existing tools, on-chain)
output = skill-research.md

[rubric_step_2]
criteria_1 = Product-Market Fit (7đ): Bằng chứng user CẦN skill, tạo DEMAND (thu hút user, drive share purchases)
criteria_2 = Sáng tạo & Độc đáo (5đ): Góc nhìn mới, kết hợp AI + on-chain + UX, niche chưa ai phục vụ
criteria_3 = Visibility & Monetization (5đ): Strategy Public/Private có cơ sở, so sánh đối thủ, logic rõ ràng
criteria_4 = Chất lượng Nghiên cứu (5đ): Số liệu có nguồn, verify (không chỉ AI), phân tích sâu
criteria_5 = Tính khả thi Kỹ thuật (3đ): Skill build được với tech hiện tại, không viễn vông

[key_points]
pmf_critical = PMF chiếm 7/25 điểm — demand thực > skill sáng tạo
quality_over_quantity = 5 skill chất lượng > 10 skill qua loa
evidence_required = "Em nghĩ nhiều người cần" ≠ bằng chứng. Số liệu mới là bằng chứng

status = done

# -----------------------------------------------------------------------------
# DELIVERABLE 3: DISTRIBUTION PLAN (40%)
# -----------------------------------------------------------------------------

[step_3]
name = Distribution Plan
weight = 40% (phần QUAN TRỌNG NHẤT)
reason = Trả lời: "Làm thế nào để người dùng biết đến platform trong tháng đầu với $10K?"
budget = $10,000 cho tháng đầu tiên
tasks = Đề xuất 3–5 kênh acquisition cụ thể (≥1 organic, ≥1 paid) | Mỗi kênh: Tại sao chọn, Action plan chi tiết (làm gì, đăng đâu, target ai), Timeline (tuần nào làm gì), Estimated reach, Cost, Metric (đo kết quả) | Phân bổ $10K vào các kênh, giải thích tại sao | (Bonus) Partnership: tên đối tác cụ thể, lý do, lợi ích 2 bên, action plan
output = distribution-plan.md

[requirements]
minimum_channels = 3-5 kênh
organic_required = ≥1 kênh organic ($0)
paid_required = ≥1 kênh paid
budget_limit = Tổng paid ≤ $10,000
detail_level = Intern đọc xong biết CHÍNH XÁC làm gì ngày mai

[not_acceptable]
vague_answer = "Làm SEO", "Đăng Twitter", "Partnership" (đó là tiêu đề, không phải plan)
no_budget = Không nói rõ $10K phân bổ như thế nào
no_metrics = Không có cách đo kết quả
no_timeline = Không rõ tuần nào làm gì

[acceptable]
specific_action = "Week 1: Viết 8 bài/tháng tutorial trên Mirror.xyz, mỗi bài về 1 skill"
budget_breakdown = "$5K Twitter Ads (50%), $3K KOL (30%), $1.5K Reddit (15%), $500 bounties (5%)"
metrics_clear = "CPC $0.50, CTR 3%, conversion 3%, CAC $16.67"
timeline_weekly = "Week 1: Setup, Week 2: Scale winners, Week 3: A/B test, Week 4: Retarget"

[intern_test]
question = "Nếu sếp giao plan này cho intern, intern có thực hiện được không?"
pass = Plan đủ chi tiết (action, budget, metric, timeline) → intern execute được
fail = Plan chỉ là list ý tưởng → intern không biết bắt đầu từ đâu

status = done

# -----------------------------------------------------------------------------
# STEP 4: AI SHOWCASE + DATA
# -----------------------------------------------------------------------------

[step_4]
name = AI Showcase + Data
reason = Show BGK cách dùng AI để research hiệu quả (điểm cộng)
tasks = Screenshot hoặc link các prompt AI ưng ý nhất | Prompt research đối thủ, phân tích demand, viết distribution plan | Workflow kết hợp nhiều AI tool (Claude + ChatGPT + Perplexity) | Số liệu/chart có nguồn trong data/
output = ai-showcase/ (screenshots/links), data/ (numbers, charts)

[showcase_suggestions]
prompt_types = Research đối thủ | Phân tích demand | Channel strategy | Unit economics | Timeline planning
workflow_example = Claude research + ChatGPT verify + Perplexity fact-check

[warning]
ai_hallucination = AI HAY BỊA SỐ LIỆU (user count, revenue, market size)
must_verify = LUÔN verify số liệu bằng nguồn gốc (website, GitHub, on-chain)
bgk_will_ask = "Số này lấy ở đâu?" — Nếu "AI cho em" mà không verify = trừ điểm

status = pending

# -----------------------------------------------------------------------------
# STEP 5: README + WEB PRESENTATION
# -----------------------------------------------------------------------------

[step_5]
name = README + Web Presentation
reason = BGK sẽ pull repo về soi + presentation là nơi defend
tasks = README: giới thiệu project + link web presentation | Web presentation (BẮT BUỘC Gemini Canvas): Competitive (3p) → Skill (4p) → Distribution (5p) → AI Showcase (2p) → Q&A (5-8p) | Push toàn bộ lên GitHub TRƯỚC buổi present
output = README.md có link presentation, web presentation sẵn sàng

[presentation_format]
tool_required = Gemini Canvas (BẮT BUỘC, KHÔNG dùng PowerPoint/Google Slides)
total_time = 15-20 phút
structure = Competitive 3p | Skill 4p | Distribution 5p | AI Showcase 2p | Q&A 5-8p

[bgk_questions]
q1 = "Đối thủ X có 50K user, tại sao marketplace mình sẽ thắng?" → Cần số liệu, không phải ý kiến
q2 = "Skill này có ai cần không? Drive user đến platform không?" → Bằng chứng demand (search volume, existing tools)
q3 = "$10K budget có đủ để có 1,000 user không?" → Unit economics: CPC, conversion, CAC
q4 = "Tại sao user không dùng ChatGPT thay vì platform?" → Giá trị khác biệt (on-chain data, wallet integration)

status = pending

# -----------------------------------------------------------------------------
# REPO STRUCTURE (theo GUIDEBOOK)
# -----------------------------------------------------------------------------

[repo_structure]
required_files = README.md | competitive-landscape.md | skill-research.md | distribution-plan.md | ai-showcase/ | data/

repo-name/
├── README.md                    (giới thiệu project + link presentation)
├── competitive-landscape.md     (Deliverable 1 - 25%)
├── skill-research.md            (Deliverable 2 - 25%)
├── distribution-plan.md         (Deliverable 3 - 40%)
├── ai-showcase/                 (screenshot prompt AI)
└── data/                        (số liệu, chart, research data)

# -----------------------------------------------------------------------------
# CHECKLIST TRƯỚC KHI PRESENT
# -----------------------------------------------------------------------------

[checklist]
github = GitHub repo đã public, link đã gửi vào group Telegram
presentation = Web Presentation đã tạo bằng Gemini Canvas, link dán trong README.md
deliverable_1 = Competitive Landscape: ≥5 đối thủ, có số liệu, có phân tích, có kết luận
deliverable_2 = Skill Research: 5-10 skill, mỗi skill có target user + problem + alternative + pricing + bằng chứng demand
deliverable_3 = Distribution Plan: kênh cụ thể, mỗi kênh có action plan + timeline + metric + budget allocation
channels = Có ≥1 kênh organic ($0) và ≥1 kênh paid trong Distribution Plan
github_pushed = Tất cả deliverable đã push lên GitHub
ai_showcase = Có screenshot/link prompt AI ưng ý nhất
ready_qa = Sẵn sàng trả lời phản biện BGK
know_diff = Biết marketplace mình khác đối thủ ở đâu
know_value = Biết giải thích tại sao user muốn dùng skill và hold shares
verify_data = Mọi số liệu đã verify từ nguồn gốc (không chỉ từ AI)

# -----------------------------------------------------------------------------
# KEY PRINCIPLES (từ GUIDEBOOK)
# -----------------------------------------------------------------------------

[principles]
market_first = Hiểu thị trường > Code nhanh
selling_first = Biết bán > Biết build
concrete_first = Kế hoạch cụ thể > Ý tưởng chung chung
quality_first = 5 skill chất lượng > 10 skill qua loa
detail_first = 3 kênh chi tiết > 5 kênh 2 dòng

[scoring]
total = 100 điểm
competitive = 25%
skill = 25%
distribution = 40% (phần QUAN TRỌNG NHẤT)
presentation = 10%

# -----------------------------------------------------------------------------
# TÓM TẮT WORKFLOW
# -----------------------------------------------------------------------------

[workflow]
day_1 = Competitive Landscape: Research đối thủ + số liệu + phân tích
day_2 = Skill Research: Brainstorm skills + bằng chứng demand + pricing | Distribution Plan bản 1
day_3 = Distribution Plan hoàn thiện + Review toàn bộ + Gemini Canvas presentation
day_4 = PRESENTATION 15-20p + Q&A với BGK | Push GitHub

[final_output]
github_repo = Public repo với 3 .md files + ai-showcase/ + data/
web_presentation = Gemini Canvas (BẮT BUỘC, không PowerPoint/Slides)
ready_to_defend = Trả lời được phản biện BGK với số liệu và logic
