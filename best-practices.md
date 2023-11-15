# Best Practices for Documentation

Source: ChatGPT (Open AI)

## Product Communication Types

|                                        | Engagement Features (Messaging Elements) | Focus & Purpose | User Expectations |
| -------------------------------------  | ---------------------------------------- | --------------- | ----------------- |
| **Documentation**                      | Authoritative, Informative, Precise       | Provides instructional information about the product's features and guidelines | Expect clear, comprehensive, and accurate guidance |
| **Announcements**                      | Confident, Forward-Looking, Informative   | Informs about new features, updates, or changes in the product | Anticipate clear and timely information about what's changing |
| **Release Notes**                      | Transparent, Informative, Engaging        | Details changes, improvements, and bug fixes in product updates | Look for a clear breakdown of changes and how they affect usage |
| **E-Learning/Education (Academy)**     | Supportive, Encouraging, Empowering      | Educates users through tutorials, courses, or resources on product usage | Seek step-by-step, easy-to-understand guidance to improve skills |
| **Customer Support/Service**            | Empathetic, Patient, Solution-Oriented   | Assists users with queries, issues, or guidance related to the product | Expect responsive and helpful assistance in problem resolution |
| **Marketing Material**                 | Persuasive, Aspirational, Engaging       | Promotes the product, highlighting benefits and persuading engagement | Anticipate compelling information about the product's value |
| **Community/Forums**                   | Supportive, Collaborative, Informative   | Fosters interaction, discussions, shared experiences among users | Seek advice, shared experiences, and solutions in a collaborative environment |
| **Feedback/Surveys**                   | Receptive, Open-Minded, Appreciative     | Gathers opinions, suggestions, and feedback for product improvement | Expects a platform to express opinions and see improvements based on feedback |

### Emotional Engagement Index

We asked AI to sort the mentioned engagement features using the emotional engagement index (emotional relevance metric). The range was determined by the distinct emotional impact of the provided characteristics.

Why is it relevant? The emotional engagement index affects the overall tone and writing style across various communication types.

- Authoritative: 2
- Precise: 2
- Informative: 3
- Transparent: 3
- Forward-Looking: 4
- Confident: 4
- Engaging: 4
- Supportive: 5
- Collaborative: 5
- Receptive: 5
- Open-Minded: 5
- Appreciative: 5
- Empowering: 6
- Encouraging: 6
- Empathetic: 6
- Patient: 6
- Solution-Oriented: 6
- Persuasive: 7
- Aspirational: 7

Average emotional engagement index for each product communucation type:

- Documentation: 2.33
- Announcements: 3.67
- Release Notes: 3.67
- Community/Forums: 5
- E-Learning/Education (Academy): 5.6
- Customer Support/Service: 5.75
- Feedback/Surveys: 6
- Marketing Material: 6.33

## Things to Avoid in Documentation

- **Jargon Overload:** Avoid using excessive technical jargon or industry-specific terms without providing clear explanations. Use language that's easily understood by the intended audience.

- **Marketing Language:** Steer clear of promotional or overly persuasive language. Documentation should inform and guide, not sell the product.

- **Assumptions about User Knowledge:** Don't assume users have the same level of expertise as the document creators. Provide comprehensive explanations, even for seemingly basic concepts.

- **Incomplete or Outdated Information:** Ensure the documentation is up to date and comprehensive. Incomplete or obsolete information can mislead users and cause frustration.

- **Unclear Structure and Formatting:** Maintain a clear, consistent structure throughout the documentation. Unclear organization or inconsistent formatting can make it challenging for users to find information.

- **Lack of Visual Aids:** Avoid excessive text without visual support. Utilize images, diagrams, and examples to enhance understanding.

- **No Actionable Guidance:** Ensure that the documentation offers clear, step-by-step guidance for users to achieve their goals. Vague instructions or unclear steps can be frustrating.

- **Overlooking User Feedback:** Don't disregard user feedback. Incorporate user suggestions and issues into documentation improvements.

- **Neglecting Searchability:** Ensure the documentation is easily searchable. Use clear headers, keywords, and a comprehensive index for quick navigation.

- **Overuse of Passive Voice:** Minimize the use of passive voice as it can make instructions less direct and engaging.

- **Overly Lengthy Content**: Avoid unnecessarily long paragraphs or explanations. Aim for concise and clear content to keep users engaged and focused.

## Best Practices for Documentation

- **Use Active Voice:** Frame sentences in the active voice to make instructions more direct and engaging. For instance, instead of saying "The action was performed by the system," use "The system performed the action."

- **Concise Language:** Keep sentences and paragraphs concise. Avoid unnecessary words or overly elaborate explanations. Best practice: no more than 3 sentences per paragraph.

- **Consistent Terminology:** Maintain consistent terminology throughout the documentation. Use the same words for the same concepts to avoid confusion.

- **Descriptive Headings and Subheadings:** Create informative and clear headings and subheadings that accurately represent the content that follows.

- **Use Bulleted or Numbered Lists:** Break down information into lists for easier comprehension. Use bullets for unordered information and numbers for ordered steps.

- **Plain Language Approach:** Write in a manner that's accessible to users with varying levels of expertise. Explain technical terms and acronyms when they are used.

- **Practical Examples:** Incorporate practical examples and use cases to illustrate how to apply the information in real-world scenarios.

- **Consistent Tone and Style:** Maintain a consistent tone and style throughout the documentation. Align it with the brand's voice and the user's expectations.

- **Frontload Information:** Put the most critical information at the beginning of sections or sentences to grab the reader's attention and communicate the key points upfront.

- **Use Cross-References:** Link related sections or documents to facilitate further understanding and context.

- **Empathetic and Solution-Oriented:** Frame the documentation with a focus on solving user problems. Acknowledge the user's challenges and offer solutions.

- **Provide Context and Why Statements:** Explain the context and rationale behind instructions. Users should understand why certain actions are necessary.

# User Journeys for Developer Docs

Here are supporting arguments for why the concept of user journeys might not directly apply to developer documentation:

- Objective Differences: User documentation primarily focuses on guiding end-users through product functionalities to achieve specific tasks or goals. Developer documentation, on the other hand, often revolves around APIs, SDKs, and technical aspects, aiming to assist developers in integrating or building on the product's infrastructure. These objectives might not align with a linear user journey but rather cater to varied technical needs.

- Technical Proficiency: Developer documentation typically targets an audience with a high level of technical expertise. Their journey involves accessing specific technical information, troubleshooting, and leveraging advanced functionalities. Their interaction with the documentation might not follow a predefined, linear path but could involve cross-referencing multiple sections based on their immediate needs.

- Varied Paths to Solutions: Unlike end-users who might follow a sequential process in achieving specific tasks, developers often have multiple paths to reach a solution. Their workflow might involve experimenting, testing, and adapting their approach, making their journey less linear and more exploratory.

- Focus on Reference Material: Developer documentation commonly serves as a reference material or a technical guide rather than a guided journey. It's structured to provide in-depth technical information, code samples, API references, and troubleshooting tips, catering to a different usage pattern compared to the step-by-step user journey.

However, while the concept of user journeys might not directly translate to developer documentation, considering the workflow or flow of actions developers undertake to achieve specific technical outcomes can still be valuable. Framing the content in a structured manner, anticipating the steps or phases developers might go through, and providing comprehensive, navigable documentation could enhance the developer experience without strictly adhering to the traditional user journey model.

Certainly! Here's a prompt you can use to guide a technical writer in checking documentation against the Google Developers Style Guide:

---

## Documentation Review Prompt

#### Objective:
The objective of this review is to ensure that the documentation aligns with the guidelines outlined in the Google Developers Style Guide. The focus is on maintaining consistency, clarity, and accessibility throughout the documentation.

#### Instructions:
1. **Readability and Clarity:**
   - Check for clear, concise, and easily understandable language. Avoid jargon or overly technical terms unless necessary.

2. **Structure and Formatting:**
   - Ensure consistent formatting, headings, and subheadings across all sections.
   - Confirm the use of bullet points, numbered lists, and code blocks adheres to the style guide.

3. **Grammar and Language:**
   - Review grammar, punctuation, and sentence structure for correctness.
   - Verify that active voice is preferred over passive voice for better readability.

4. **Code and Examples:**
   - Confirm that code snippets are formatted properly and follow the code style recommended in the guide.
   - Validate that examples provided are relevant, concise, and easy to follow.

5. **Accessibility and Inclusivity:**
   - Check that the documentation is accessible and accommodates diverse audiences.
   - Ensure the content is inclusive and does not contain biased language.

6. **References and Citations:**
   - Ensure all external references, citations, or attributions are appropriately documented.

7. **Overall Consistency:**
   - Evaluate consistency in terminology, capitalization, and usage of technical terms throughout the documentation.

#### Additional Notes:
Please provide feedback on any areas where the documentation may not align with the Google Developers Style Guide. Highlight specific sections or examples that require modification or improvement. Aim to maintain consistency, readability, and adherence to the style guide in all aspects of the documentation.
