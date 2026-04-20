# Daily Reflection Tree – Design Write-up

## 1. Why I chose these questions

The goal of this reflection tree is to help users think about their daily behavior in a structured and simple way. I designed the questions to be clear, relatable, and easy to answer, especially for someone who is tired at the end of the day.

For Axis 1 (Responsibility), the questions focus on whether the user takes ownership of their actions or feels controlled by external situations. The options are designed to capture both internal and external reactions without judging the user.

For Axis 2 (Contribution), the questions help identify whether the user focused on giving value or expecting from others. The aim was to make entitlement visible without making the user uncomfortable.

For Axis 3 (Thinking Radius), the questions explore whether the user thinks only about themselves or considers others such as teammates or customers. This helps expand perspective.

---

## 2. How I designed the branching

The tree starts with a general question about the user’s day. Based on the answer, it branches into two paths — positive or negative experience.

Each branch leads to follow-up questions that dig deeper into the user’s mindset. Decision nodes are used to route users based on their answers.

Bridges are used to smoothly transition between the three axes:
- Axis 1 → Axis 2 (Responsibility → Contribution)
- Axis 2 → Axis 3 (Contribution → Thinking)

This creates a natural flow instead of making it feel like separate questions.

---

## 3. Psychological concepts used

The design is based on three key psychological ideas:

- Locus of Control: Understanding whether a person believes they control outcomes or external factors do.
- Contribution vs Entitlement: Identifying whether the person focuses on giving value or expecting rewards.
- Self vs Others Thinking: Expanding thinking from self-centered to team or customer-centered.

These concepts help users reflect without feeling judged.

---

## 4. Design decisions and trade-offs

I kept the number of options limited (4 per question) to avoid confusion. The language is simple so that users can quickly understand and respond.

Instead of complex logic, I used clear branching so that the system remains fully deterministic.

The reflections are short and neutral, avoiding any moral judgment.

---

## 5. What I would improve

With more time, I would:
- Add more nodes to increase depth of reflection
- Improve summary by using more personalized responses
- Build a simple UI for better user experience
- Test with real users and refine questions

---

## Conclusion

This reflection tree helps users move from awareness to improvement by guiding them through responsibility, contribution, and perspective. The system is fully deterministic and ensures consistent reflection every time.