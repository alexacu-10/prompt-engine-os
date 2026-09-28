# ⚡ Prompt Engine OS — Production-Grade XML Skills for Claude

> 🚀 **Get the complete 5-Skill Bundle + Python Validation Suite on Gumroad:**  
> 👉 **[https://alexacu10.gumroad.com/l/pxkikj](https://alexacu10.gumroad.com/l/pxkikj)**

Stop sending plain text prompts to Claude. Plain text leads to soft, generic output, ignored constraints, and AI filler words ("I hope this finds you well").

**Prompt Engine OS** uses structured XML tags (`<system_instruction>`, `<constraints>`, `<output_template>`) to force Claude 3.5 & 3.7 into a precise execution engine state.

---

## 📦 What's Included in the Full OS Bundle

1. **Sales Sequence Engine:** 4-touch cold outreach sequences, subject lines & calling scripts.
2. **SEO Content Architect:** Search-intent long-form articles with JSON-LD schema markup.
3. **Executive Minutes Synthesizer:** RACI action matrices & executive summaries from transcripts.
4. **Client Onboarding Brief:** Project charters, scope matrices (In/Out of scope) & risk registers.
5. **SaaS PRD Architect:** Engineering-ready PRDs with Given-When-Then (Gherkin) criteria.
6. **Automated Validation:** Includes `validate_skills.py` test suite.

👉 **[Get Instant Access on Gumroad](https://alexacu10.gumroad.com/l/pxkikj)**

---

## 💡 Free Sample Architecture: Executive RACI Minutes

```xml
<system_instruction>
You are an executive operations lead. Synthesize meeting transcripts into actionable minutes with RACI matrix mapping.
</system_instruction>

<constraints>
- No filler language ("In summary", "It was discussed").
- Format action items strictly as: [Task] | [Responsible] | [Accountable] | [Deadline].
- Enforce strict Markdown table schema.
</constraints>
