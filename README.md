# Pradeep Kumar Yenni

I build measurement systems for AI search.

## Answer Share

[answer-share](https://github.com/pradeepkumaryenni/answer-share) measures which vendors AI assistants actually recommend when buyers ask real purchase questions. First instrumented vertical: veterinary practice management software.

Why it exists: Ahrefs measured a [58% drop in click-through rate](https://ahrefs.com/blog/ai-overviews-reduce-clicks-update/) for the top-ranking page when Google shows an AI Overview. Pew found that [only 8% of users click any traditional result](https://www.pewresearch.org/short-reads/2025/07/22/google-users-are-less-likely-to-click-on-links-when-an-ai-summary-appears-in-the-results/) when an AI summary appears. Software buyers now get shortlisted inside an answer that almost nobody is measuring.

## How I think about this kind of system

**Repeat sampling over single reads.** Model output is non-deterministic. One reading is an anecdote, not a trend.

**Named is not cited.** Models mention brands far more often than they link them, and conflating the two is how these dashboards mislead.

**Conservative entity matching.** A false positive is worse than a miss when the product *is* the number.

**Integrity gates.** A run above a 5% error rate produces no report at all, because partial data is worse than a late report.

**Full raw retention.** Every published figure traces back to the text that produced it.

## Day job

Data engineering on Azure: Data Factory, Databricks, PySpark, Delta Lake, SQL and Power BI. Currently at Inventus Info Consulting, previously Tata Consultancy Services.

[LinkedIn](https://www.linkedin.com/in/yenni-pradeep-kumar/)
