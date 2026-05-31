---
name: review-reply-generator
description: Generate polite public replies and optional private follow-up notes for Google, Yelp, Xiaohongshu, and local platform reviews without fabricating facts or exposing private customer data.
---

# Skill: review-reply-generator

## 中文注释

这个 skill 用于公开评论回复，适合 Google、Yelp、小红书、本地平台等评价场景。回复应礼貌、真实、保护隐私，不得编造客户经历、争议细节、补偿承诺或私人信息。

## Purpose

Draft helpful, privacy-safe replies to positive, neutral, and negative customer reviews.

## Best for

Local businesses replying to public reviews across Google, Yelp, Xiaohongshu, and local platforms.

## Not for

Fake reviews, review manipulation, private customer disclosure, legal threats, or fabricated incident details.

## Input

- Business type
- Platform
- Review text
- Review sentiment
- Known facts
- Desired tone
- Resolution policy
- Things to avoid
- Language

## Output

1. Review summary
2. Reply goal
3. Public reply
4. Optional private follow-up
5. Tone notes
6. What not to mention
7. Escalation suggestion
8. Risky wording to avoid
9. Final review checklist

## Process

1. Identify sentiment and issue type.
2. Separate known facts from assumptions.
3. Draft a short public reply.
4. Add optional private follow-up when needed.
5. Remove private data and risky claims.

## Quality Bar

- Keeps replies polite and concise.
- Does not expose private customer data.
- Does not fabricate review details.
- Handles negative reviews calmly.
- Avoids guarantees or admissions beyond known facts.

## Example Input

Business type: pet grooming store
Platform: Google
Review sentiment: negative
Review text: appointment was delayed and communication was unclear
Known facts: staff can invite the customer to contact the store

## Example Output

Public reply: Thank you for sharing this feedback. We are sorry the appointment communication did not meet expectations. Please contact our team directly so we can understand what happened and improve the experience.

## Safety / Compliance Notes

Do not fabricate customer reviews, private details, compensation, legal facts, or service history. Do not encourage fake reviews or review manipulation.
