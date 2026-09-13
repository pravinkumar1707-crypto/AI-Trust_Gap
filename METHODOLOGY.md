# Methodology and Limitations

## Dataset
Stack Overflow Developer Survey 2025 respondent-level public dataset.

## Sample
- 49,191 respondent records in the working file.
- 33,297 respondents answered the AI accuracy/trust question.

## Trust classification
- Trust: Highly trust; Somewhat trust
- Neutral: Neither trust nor distrust
- Distrust: Highly distrust; Somewhat distrust

## Statistical approach
Segment-level distributions were compared using chi-square tests. Cramér's V is reported as the main measure of association strength because large samples can make very small differences statistically significant.

## Boundaries
This analysis is observational and cross-sectional. It cannot establish whether AI usage causes trust, whether trust causes AI adoption, or whether both are driven by other variables. Trust and perceived capability are self-reported constructs. Phase 1 does not directly measure objective decision quality.

## Reproducibility note
The first trust-classification implementation mistakenly treated “Neither trust nor distrust” as distrust due to substring matching. This was detected during validation and corrected before the final portfolio analysis.
