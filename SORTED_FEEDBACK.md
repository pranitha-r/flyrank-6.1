# Feedback Categorization: Must-Fix vs Nice-to-Have

Criterion for sorting:
- **Must-Fix**: Confusing, broken, hurts the primary conversion action (booking 15-min discovery call), or prevents the proof claim from landing.
- **Nice-to-Have**: Aesthetic refinements, additional polish, or non-blocking additions that can be done later.

---

## 🔴 Must-Fix (Addressing Now)

1. **Replace Case Study Placeholders with Real Technical Proof & Metrics**
   - *Why:* If the case study only contains placeholder text, the proof claim ("I prove I can define, scope, and build...") doesn't land. The reviewer specifically called this out as the blocker to believing the claim.
   - *Action:* Detail the actual multi-agent pipeline architecture (LangChain/LangGraph/Python), problem scoped, tool usage, latency/eval metrics, and GitHub repo link.

2. **Fix Mobile Responsiveness for the Calendly Widget & Layout**
   - *Why:* Hurts the "One Target Action" (scheduling a 15-minute call) if mobile users experience awkward horizontal scrolling or overflow.
   - *Action:* Constrain the widget container with responsive CSS (`width: 100%; max-width: 100%; overflow: hidden;`).

3. **Add Direct Code & Architecture Proof Links**
   - *Why:* Directly substantiates "using LLM orchestrators and python" with real artifacts.
   - *Action:* Add badges/links for GitHub Repo, System Architecture Diagram, and Tech Stack tags.

---

## 🟢 Nice-to-Have (Later)

1. **Resume Download Button**
   - *Why:* Useful for hiring managers, but the Calendly technical discovery call is our single target conversion action. We will add a resume link in the footer/About section later.

2. **Animation / Transitions for Theme Toggle**
   - *Why:* Enhances visual delight, but does not affect whether the proof claim lands or the user books a call.

3. **Interactive Live Demo Embed**
   - *Why:* A live hosted Streamlit/Gradio embed would be great, but static code walkthrough + video/repo link is sufficient for the MVP proof.
