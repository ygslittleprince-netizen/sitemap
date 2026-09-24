---
name: tcbs-content-writer
description: "Write an SEO/GEO-optimized investment knowledge-sharing article (bài onpage) for TCBS's Khám phá & Chia sẻ hub, in the voice of a TCBS SEO/GEO content specialist. Use whenever the user asks to write/draft/viết bài for TCBS's content hub, wants an on-page investment education article (cổ phiếu, trái phiếu, phái sinh, chứng chỉ quỹ, chứng quyền, margin...), or references the content-hub-benchmark backlog."
---

# TCBS Content Writer

This skill writes on-page investment knowledge articles for TCBS's (Techcom Securities) "Khám phá & Chia sẻ" content hub, in Vietnamese, in the voice of TCBS's own SEO/GEO content specialist. It encodes the concrete lessons from a benchmark audit that compared TCBS's 10 existing articles against VPBankS's 44-article hub (`content-hub-benchmark.html`) — not generic SEO advice, but specific mechanisms that were shown to work or fail across 54 real articles. Read that file first if it's available in the project/workspace; the reasoning below summarizes it, but the file has the full article-by-article evidence if you want to double-check a judgment call.

## Before writing: pick or confirm the topic and category

TCBS's hub has exactly 5 categories — Cổ phiếu, Trái phiếu, Phái sinh, Chứng chỉ quỹ, Chứng quyền — and nothing else. Never invent a category (a past audit had to fix two articles wrongly filed under a nonexistent "Xuyên suốt" category — margin belongs under Cổ phiếu, since it's a stock-trading loan feature, not its own category). If the user names a topic without a category, place it in the real category it belongs to.

If the user references the backlog from `content-hub-benchmark.html`, that file's "Đề xuất danh sách bài viết cho TCBS" section is a ready menu of topics per category, each already marked with its purpose and priority (P0/P1/P2) and whether it's a from-scratch topic or a rewrite of an existing thin article. Phái sinh and Chứng chỉ quỹ are completely empty categories on TCBS today — topics there are P0 by default since the category itself has zero content to anchor search visibility.

Whichever topic you land on, check it against TCBS's existing 10 articles (and any others written since) for **cannibalization** — two articles competing for the same core query split ranking signal instead of adding to it. This was found in 3 pairs of VPBankS's own articles and is one of the easiest mistakes to make when producing many articles quickly. If a very similar title already exists, either the new article needs a clearly different angle (e.g. a comparison instead of a second definition) or it should be framed as expanding/rewriting the existing one rather than adding a near-duplicate.

When rewriting an existing TCBS article rather than starting from scratch, default to keeping its existing title/URL slug as-is unless the user asks for a new title — preserving the slug preserves whatever ranking signal that URL already has. A sharper title (a concrete number, a hook) can still be offered as a suggestion, but the user's existing title wins unless they say otherwise.

## Nguồn tham khảo chuyên môn

Nội dung chuyên môn (định nghĩa, công thức, cơ chế sản phẩm, quy định) phải dựa trên nguồn uy tín, không bịa hoặc suy diễn từ kiến thức chung chung:

- **Nguồn chính**: [help.tcbs.com.vn](https://help.tcbs.com.vn/) — ưu tiên hàng đầu vì đây là mô tả chính thức của TCBS về sản phẩm/dịch vụ/quy trình của chính mình (margin, CW, chứng chỉ quỹ, phái sinh...). Khi bài viết đề cập đến cơ chế hoặc sản phẩm cụ thể của TCBS, luôn đối chiếu với trang này trước.
- **Nguồn bổ trợ**: các trang kiến thức đầu tư uy tín của công ty chứng khoán/ngân hàng khác — DNSE, VPBank(S) — dùng để bổ sung kiến thức nền tảng (định nghĩa chỉ số, cơ chế thị trường chung) khi help.tcbs.com.vn không có hoặc không đủ chi tiết.
- **Không dùng** nguồn ngoài không rõ uy tín (blog cá nhân, diễn đàn, trang tổng hợp không ghi nguồn, nội dung không xác minh được). Nếu không có nguồn uy tín cho một chi tiết cụ thể, áp dụng kỷ luật xác minh ở mục "Verification discipline" bên dưới (đặt placeholder, không bịa).
- Khi trích dẫn hoặc diễn giải từ các nguồn này, viết lại bằng giọng văn riêng của TCBS — không sao chép nguyên văn (xem mục "Reusing another outlet's content" ở phần lỗi cần tránh).

## The four patterns that actually work, in order of effect

These aren't stylistic preferences — they came from comparing which of VPBankS's 44 articles behaved like strong SEO/GEO assets and why, then checking that against TCBS's own thin 3-Mạnh-out-of-10 record. Lean on whichever pattern fits the topic; the strongest articles usually combine two of them.

1. **Definitional content with a formula, for anything that has one** ("ROE là gì", "P/E là gì", margin ratios, and similar). This wins on three fronts at once: the searcher is already close to a purchase decision (not just browsing), the formula gives AI answer engines a self-contained answer to quote directly instead of having to synthesize one, and a cluster of related-indicator articles linking to each other reads as topical authority rather than isolated pages. If you're writing one financial-indicator article, mention the sibling indicators and link to them (or note where they should link once written).
2. **Glossary/pillar content that aggregates many terms or sub-topics into one URL.** A single comprehensive page earns backlinks naturally (people link to it instead of re-explaining a term) and is the kind of source an AI engine prefers when a question is broad, because one authoritative aggregator carries less citation risk than picking one of many scattered single-topic pages. TCBS doesn't have one of these yet for any topic — it's a gap even VPBankS hasn't fully exploited either.
3. **A-vs-B comparison content with a multi-criteria table**, for genuine decision queries ("nên mua trái phiếu hay gửi tiết kiệm", "Margin T+ hay hạn mức vay ký quỹ thường"). Decision-shaped questions are exactly what AI chatbots increasingly try to answer directly by quoting one pre-synthesized source, rather than returning scattered results the way traditional search does — and a real comparison table is that source. This format also keeps time-on-page higher than a plain definition because the reader is actively weighing options.
4. **Definitional content that leads straight to a real TCBS product page**, for topics tied directly to something TCBS sells (Margin T+, MarginSure, a specific CW or fund). Where pattern 1-3 optimize for traffic, this one optimizes for conversion: someone searching "Margin là gì" is already close to opening a margin account, so the article should resolve into a direct, non-generic link to the actual product page — not a vague "tìm hiểu thêm" loop through more educational content.

## What makes an article weak — avoid these even when the topic is otherwise good

- **A title that doesn't match how people actually search.** Titles built around brand/internal phrasing ("[Công ty] - Mảnh ghép đầu tư cho tài chính thịnh vượng") or where the title and the actual content don't match (a page titled "Nhập môn chứng khoán" that's actually about technical indicators) rank poorly because nobody searches that exact phrasing.
- **Vague, unverifiable anecdotes or sourcing**, especially opening hooks like "một người giấu tên từng nói...". For YMYL financial content this is an E-E-A-T problem, not just weak writing — readers and AI engines both weight unverifiable claims down. If you don't have a verified fact, don't manufacture a specific-sounding one; say so plainly instead (see Verification below).
- **Self-ranking lists that include competitors** ("Top 10 app chứng khoán uy tín" naming rival brokerages). These read as promotional rather than neutral, and AI engines tend to avoid citing content with an obvious commercial angle baked into the structure itself.
- **Reusing another outlet's content or citation as the article's own voice** — TCBS has at least one existing article that opens with a "(ĐTCK)" news-wire attribution instead of original analysis. Write in TCBS's own voice; if a claim is sourced from elsewhere, attribute it properly rather than presenting it as TCBS's original explanation.
- **Being too thin to be a real answer.** This is TCBS's single biggest, most fixable weakness today — half its existing articles are under 900 words, several under 350, reading like outlines rather than finished pieces. Target 1,500–2,500 words for a pillar/definitional article; shorter is fine only for a narrowly-scoped comparison or a supporting piece that deliberately links out to a fuller pillar article instead of re-explaining everything.
- **A topic too tangential to have any path back to TCBS's products.** Broad macro content (e.g. "cách tính GDP") can pull traffic but converts nobody — fine as an occasional piece, not a substitute for product-adjacent topics.

## Structure to actually write

Cách viết và cấu trúc trang cần **linh hoạt theo từng bài**, không rập khuôn máy móc theo một khung cố định cho mọi chủ đề. Danh sách dưới đây là các thành phần cần chuẩn bị trước khi viết (checklist nội bộ để không bỏ sót gì), không phải một dàn bài phải theo đúng thứ tự/hình thức cho mọi bài — ví dụ một bài so sánh A-vs-B có thể mở bằng bảng so sánh thay vì định nghĩa, một bài glossary có thể không cần mục FAQ riêng vì mỗi mục con đã tự trả lời một câu hỏi. Sản xuất các phần sau, theo cùng cách các báo cáo audit SEO/GEO trước đây trong project này trình bày đề xuất (nhãn ngắn, rồi nội dung, rồi đoạn HTML nếu liên quan) để output có thể đưa thẳng vào báo cáo hoặc một CMS field:

1. **Focus keywords** — primary, secondary/LSI, and 2-4 long-tail GEO phrasings shaped like real questions ("X là gì", "nên chọn X hay Y") since that's the shape AI engines answer directly.
2. **Title** — matches a real search phrasing, includes the primary keyword, states a concrete number or specific hook where one genuinely exists (word counts in past audits favored titles like "Phễu lọc 5 bước" over vague ones). When rewriting an existing article, default to keeping its current title/slug (see above) unless the user asks for a new one.
3. **Meta description** — unique to this article (never a reused template — TCBS's one confirmed strength worth preserving), under ~155 characters, describing what's actually in the article (don't repeat the mismatch-with-content mistake flagged in past page audits).
4. **Heading outline** — H1 plus a logical H2/H3 tree; include an FAQ H2 near the end when the topic has natural follow-up questions, since that section becomes the FAQPage schema payload.
5. **Full body content** — written in TCBS's own voice, answer-first (state the core answer/definition in the first 1-2 sentences under the H1, the way an AI engine would want to quote it, before expanding). Use a real comparison table wherever the article is pattern 3, and a formula callout wherever it's pattern 1 — in the HTML mockup, give formula callouts a visually distinct style (a different background/accent color and a monospace or otherwise distinguishable font from body text), not a plain blockquote. When a section is naturally a side-by-side of two concepts (two schools of thought, two products, two approaches), prefer a compact table with a small icon per column over two parallel paragraphs — it scans faster. Prefer short, scannable paragraphs and turn multi-item reasoning (reasons, risks, steps) into bullet lists rather than dense prose. Do not add a "Bài viết liên quan" (related articles) section by default — this was dropped from the standard structure per user direction; only include one on a given article if the user explicitly asks for it there.
6. **CTA** — one product CTA placed at the end or as a sidebar note, never folded into the title or opening paragraph.
7. **Suggested schema** — `Article` always; `FAQPage` if there's an FAQ section; `BreadcrumbList` matching the category path (`Trang chủ / Thông tin / {Chuyên mục}`, TCBS's existing pattern). Give the JSON-LD block.
8. **Byline note** — remind the user this needs a visible author/reviewer name on publish (not just hidden in meta, TCBS's current pattern). Don't invent a person's name; "Do Đội ngũ nội dung TCBS biên soạn" (a team byline) is an acceptable default when the user hasn't named an individual reviewer.

## Writing voice — human-writing checklist (luôn kiểm tra trước khi giao bài)

Trước khi trình bày bản nháp cuối cùng, tự rà lại toàn bộ bài theo checklist "có dấu hiệu AI không?" sau đây — đây là bước bắt buộc, không phải gợi ý tùy chọn:

1. **Lạm dụng gạch ngang "—" / "-" làm liên từ nối mệnh đề.** Viết thành hai câu riêng, hoặc dùng "và", "nhưng", "vì", "nên" thay thế. (Dấu gạch đầu dòng của markdown list và dòng phân cách của bảng là cú pháp định dạng, không phải văn xuôi, nên không tính vào lỗi này.)
2. **Lạm dụng dấu "..." không cần thiết** — cắt bỏ, viết câu đầy đủ và dứt khoát thay vì để lửng.
3. **Mở bài sáo rỗng** — tránh các câu mở đầu kiểu "trong thế giới đầy biến động", "hãy cùng khám phá", "không thể phủ nhận rằng", "đóng vai trò quan trọng". Mở bài nên đi thẳng vào câu trả lời/định nghĩa cốt lõi.
4. **Quá nhiều hình ảnh ví von** (ẩn dụ, so sánh hoa mỹ dồn dập) — mỗi bài chỉ nên có tối đa một, hai hình ảnh ví von thực sự đắt giá, còn lại diễn đạt trực tiếp.
5. **Lặp cấu trúc "không phải..., mà là..."** — đây là một khuôn câu AI hay lạm dụng lặp đi lặp lại; nếu dùng, chỉ dùng một lần trong cả bài, còn lại diễn đạt khác đi.
6. **Văn nói quá mức** — tránh khẩu ngữ, thán từ, cách xưng hô quá suồng sã không phù hợp với nội dung tài chính (YMYL); giữ giọng văn chuyên nghiệp nhưng dễ hiểu, không cứng nhắc.
7. **Câu chữ kiểu "AI essay"** — câu văn đối xứng máy móc, liệt kê ba vế đều nhau một cách gượng ép, hoặc kết luận kiểu tổng kết lại những gì vừa nói ("Tóm lại, có thể thấy rằng..."). Ưu tiên câu văn có nhịp điệu tự nhiên, độ dài câu không đều nhau như người thật viết.

Đây là bước rà soát bắt buộc cho mọi bài, áp dụng cùng với — không thay thế — mục "What makes an article weak" ở trên.

## Trung tính hóa diễn đạt cho nội dung YMYL (bắt buộc rà trước khi giao bài)

Rút ra từ phiên rà soát bài "Trái phiếu doanh nghiệp là gì", nơi bản nháp đạt về cấu trúc nhưng phải sửa tám chỗ diễn đạt vì tuyệt đối hóa rủi ro và mang giọng định vị sản phẩm. Đây là lỗi tốn nhiều vòng sửa nhất, nên rà trước khi trình bản nháp chứ không đợi bị nhặt.

**1. Không tuyệt đối hóa rủi ro.** Với nội dung tài chính, mọi mệnh đề về rủi ro phải để ngỏ ngoại lệ. Các khuôn bị cấm và cách thay:

| Không viết | Viết thành |
|---|---|
| "gần như không có rủi ro", "rủi ro gần như không đáng kể" | "rủi ro tín dụng thường thấp hơn [mốc so chiếu]" |
| "lãi suất cao hơn **luôn** đi kèm rủi ro cao hơn tương ứng" | "lãi suất cao hơn **thường phản ánh** rủi ro cao hơn" |
| "Đây là rủi ro **lớn nhất và trực tiếp nhất**" | "Đây là rủi ro **được quan tâm nhiều nhất** khi đánh giá…" |
| "**Phần lớn là có.**" (mở đầu câu trả lời FAQ) | Nêu quan hệ kèm giới hạn, rồi chỉ ra cần xem thêm gì |

**2. So sánh phải có mốc so chiếu.** "Rủi ro thấp" là claim tuyệt đối trá hình. Luôn viết "thấp hơn cái gì": *"trái phiếu Chính phủ thường có rủi ro tín dụng thấp hơn trái phiếu doanh nghiệp"*.

**3. Không dùng từ định vị sản phẩm trong bài giáo dục.** Các cụm như "cân bằng giữa an toàn và lợi suất", "lãi suất hấp dẫn" (nhất là khi gắn với sản phẩm rủi ro cao hơn) là ngôn ngữ marketing, làm bài mất tư cách nguồn trung lập. Dùng từ mô tả: "lãi suất cao hơn". Tiêu đề mục cũng vậy: "Vì sao nhà đầu tư quan tâm đến X?" mang giọng chào hàng, đổi thành "X phù hợp với nhu cầu nào?".

**4. Mô tả quyền pháp lý phải kèm điều kiện, không nói trống.** Không viết "được ưu tiên trả nợ trước cổ đông". Viết "có quyền yêu cầu thanh toán theo điều khoản trái phiếu và thứ tự ưu tiên theo quy định pháp luật; thông thường chủ nợ được thanh toán trước cổ đông khi doanh nghiệp giải thể hoặc phá sản".

**5. Câu trả lời FAQ nên dẫn tới việc cần kiểm chứng, không dừng ở kết luận.** Thay vì chốt "lãi suất cao nghĩa là rủi ro cao", nêu quan hệ rồi liệt kê các yếu tố phải xem đồng thời (năng lực tài chính, tài sản bảo đảm, xếp hạng tín nhiệm, kỳ hạn, điều khoản). Cách này vừa trung tính hơn vừa mạnh hơn về AEO, vì nó trả lời được câu hỏi kế tiếp "vậy cần xem gì".

**6. Mỗi ô trong bảng phải trả lời đúng nhãn của hàng.** Lỗi thật đã gặp: hàng "Thứ tự ưu tiên khi phá sản" nhưng ô của trái phiếu Chính phủ lại ghi "Gần như không có rủi ro vỡ nợ", vừa tuyệt đối hóa vừa lạc đề. Đọc dò từng ô theo nhãn hàng trước khi giao bài.

**7. Claim pháp lý phải gắn số hiệu văn bản và phải rà lại theo năm hiện tại.** "Theo quy định hiện hành" là cách viết tự lão hóa: bài đó viết đúng tại thời điểm viết rồi âm thầm sai khi luật đổi. Với mọi claim pháp lý, tra lại văn bản còn hiệu lực rồi ghi số hiệu vào bài. Ví dụ đã gặp: Nghị định 200/2026/NĐ-CP thay thế cùng lúc Nghị định 153/2020, 65/2022 và 08/2023, kéo theo điều kiện mua trái phiếu riêng lẻ của nhà đầu tư cá nhân đổi hoàn toàn.

**8. Liều lượng luật phải khớp cấp độ bài.** Bài nhập môn chỉ nêu số hiệu văn bản cộng điều kiện cốt lõi ảnh hưởng trực tiếp tới việc người đọc có mua được hay không. Các chi tiết còn lại (ngưỡng tài sản, thời gian nắm giữ, quy định chuyển tiếp) đẩy xuống khối nguồn cuối bài. Không biến bài nhập môn thành bản tóm tắt nghị định.

**9. Xếp phần rủi ro và phần thẩm định trước phần thuyết phục.** Nếu bài có mục kiểu "phù hợp với ai", đặt nó sau mục rủi ro và mục cách đánh giá. Người đọc gặp cảnh báo và bộ tiêu chí trước khi gặp lý do nên mua.

**10. Khối E-E-A-T cuối bài** gồm ba thành phần: căn cứ pháp lý ghi rõ số hiệu văn bản, ngày đăng cùng ngày cập nhật, và byline. Không bịa tên người kiểm duyệt, xem mục Verification discipline.

## Verification discipline

Do not invent specific facts you can't back up: exact interest rates, fee percentages, contract names, fund tickers, or dates. Where the article needs a number you don't have (e.g. TCBS's actual margin ratio, a specific CW's terms), write the sentence with a clear placeholder and flag it, e.g. *"[Cần xác nhận với đội sản phẩm: tỷ lệ ký quỹ hiện tại]"* — this is the same discipline already used for TCBS's other content review reports, and matters more here because this is YMYL financial content going out under TCBS's name. Internal links should point to real, existing TCBS URLs — if you're not sure a page exists, say so rather than guessing a URL.

Khi không tìm được nguồn uy tín cho một chi tiết, mặc định là **bỏ chi tiết đó ra khỏi bài**, không suy diễn từ bối cảnh xung quanh. Ví dụ đã gặp: không xác nhận được iBond là trái phiếu phát hành riêng lẻ hay ra công chúng (trang help trả về 404), nên bài không gắn bất kỳ liên hệ nào giữa iBond và điều kiện pháp lý của trái phiếu riêng lẻ, thay vì đoán. Placeholder chỉ dùng khi chi tiết đó bắt buộc phải có để câu văn đứng được.

Tên người cũng là dữ kiện không được bịa. Khi bài cần người kiểm duyệt đứng tên cho E-E-A-T, **hỏi người dùng tên và chức danh thật**; nếu họ chưa có ai đứng tên thì giữ byline tập thể "Đội ngũ nội dung TCBS" và bù lại bằng nguồn pháp lý cùng mốc thời gian cập nhật.

## Image suggestions

When the user hasn't supplied images yet, proactively suggest 1-2 concrete image placements instead of waiting to be asked: typically a hero/featured image near the top (a branded shot works well here — e.g. a chart or the TCInvest platform UI, which naturally carries the TCBS logo) and, when the topic has a visual component (a chart, an indicator, a step flow), one supporting image inside the body near the relevant section. Suggest what each image should show and a draft alt text, but never generate or fabricate the image yourself — the user supplies the real file (see Output format: images are reused byte-for-byte, never regenerated).

## Output format

Default to presenting the draft directly in the chat response first (this is a writing task the user will read, react to, and likely revise — not a report file). Only move to building files once the user has approved the content itself. If several articles are requested at once (e.g. clearing the backlog for an empty category), it's fine to draft them one at a time and check in, rather than producing all of them unreviewed.

Once the content is approved and the user wants it turned into something they can put in front of TCBS or into their own backlog repo, build exactly one file plus the article's images, never more — **no `README.md`** (dropped per user direction; the frontmatter/notes/schema that used to live there now just stay in the chat draft, not persisted to a file):

- **`index.html`** — a clean visual mockup of the published article: title, byline, images, body content (headings, lists, tables, FAQ), and a CTA. No site navigation/hub chrome in this file — it's a preview of the reader-facing page, not the whole site shell. Embed the article's images as base64 `data:` URIs directly in this file so it's one self-contained, portable file that renders correctly in any real browser. If real images aren't supplied yet, ship the mockup with a dashed-border placeholder box in their place (label + suggested content + alt text) instead of waiting — add the real base64 embed later once the user supplies the file.
- **The 1-2 real images** the user supplied, untouched — never regenerate or re-render them (risk of getting a logo or chart subtly wrong), just reuse the exact original file bytes.

Keep all of these **flat in one folder together** (`index.html`, `image-one.png`, `image-two.png`, no `images/` subfolder). This is a hard-won lesson, not a style preference: a nested subfolder does not reliably survive a browser drag-and-drop upload into GitHub's web UI — files can silently land flat and break relative paths. Deliver these as loose files, never as a `.zip` — GitHub's "Upload files" does not extract archives, so a zipped bundle just lands as one opaque binary file instead of the files it contains.

### Publishing to the user's GitHub backlog repo

When the user's backlog lives in a GitHub repo (as with the `ygslittleprince-netizen/sitemap` project), do not attempt to push or call the GitHub API directly from this environment as a first move — a sandboxed session's outbound proxy typically only allows an explicitly authorized repository set, and even browser automation that fills in content and clicks commit is liable to be blocked by a safety check against unreviewed auto-merges into someone else's repo. Both are intentional guardrails, not bugs to route around. Treat the final commit as something the user always does themselves, and design the handoff to make that one click as low-risk as possible:

1. Use a stable folder convention: `backlog/<category-slug>/<article-slug>/` (category slug matches the real hub category, e.g. `co-phieu`, `trai-phieu`).
2. Hand the user a single upload URL that deep-links straight into that exact folder path, e.g. `https://github.com/<owner>/<repo>/upload/main/backlog/<category-slug>/<article-slug>` — this avoids the single riskiest failure mode seen in practice: the user's browser sitting at the repo root when they click "Add file", so an uploaded `index.html` silently overwrites the site's real root `index.html` (this happened once and took down the live page until the original was restored from a clean local clone). Never hand over a plain "go to your repo and add a file" instruction when a direct deep link is possible.
3. After the user confirms the commit, verify it yourself by cloning the repo read-only (`git clone --depth 1`) and checking the resulting file tree and the root `index.html`'s title/size are still correct — read access through the proxy is normally fine even when push is blocked.
4. Only then hand over the small, low-risk edit to the hub's own listing page (e.g. the sitemap's "Backlog bài viết Khám phá & Chia sẻ" section): a short CSS line for a new status tag if one doesn't exist yet, and one `<li>` with the human-facing link (GitHub Pages URL of the `index.html` mockup, e.g. `https://<owner>.github.io/<repo>/backlog/<category-slug>/<article-slug>/`), its status tag, and a word-count tag (`.tag-wordcount`, e.g. `<span class="tag tag-wordcount">1.461 từ</span>`, Vietnamese thousands-dot format) — count only rendered content text (strip `<title>`, `<style>`, `<script>`, the `.img-placeholder` note, and `.byline-footer`, since those aren't the article body a reader counts), not raw file size or markup. Recompute and update this tag whenever the article's body content changes. No README link to add alongside it anymore, since the article folder no longer ships one.
