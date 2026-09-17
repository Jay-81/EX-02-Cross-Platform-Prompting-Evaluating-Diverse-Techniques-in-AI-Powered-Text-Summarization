# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM

To evaluate and compare the effectiveness of prompting techniques
(zero-shot, few-shot, chain-of-thought, role-based) across different AI
platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task:
text summarization.

## Scenario:

You are part of a content curation team for an educational platform that
delivers quick summaries of research papers to undergraduate students.
Your task is to summarize a 500-word technical article on "The Basics of
Blockchain Technology" using multiple AI platforms and prompting
strategies.

Your goal is to determine which combination of prompting technique +
platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

### Step 1: Define the Summarization Task

1.1 Select the technical article to be summarized. 1.2 Keep the same
article as the input for all prompts. 1.3 Define the evaluation
criteria: Accuracy, Coherence, Simplicity, Speed, and User Experience.

### Step 2: Prepare the Sample Article

2.1 Use the selected article as the common input. 2.2 Do not change the
article while testing different prompts. 2.3 Use the same article across
the AI platforms for a fair comparison.

### Step 3: Apply Prompting Techniques

3.1 Apply a simple/zero-shot prompt without examples. 3.2 Apply a
structured summarization prompt. 3.3 Apply a role-based prompt by
assigning the AI the role of a technical writer. 3.4 Apply prompts with
output constraints such as word count, language level, and number of key
points. 3.5 Record the generated summary for each prompt.

### Step 4: Compare the Generated Summaries

4.1 Check whether the important information from the article is
preserved. 4.2 Check the logical flow and readability of each summary.
4.3 Check whether the language is simple enough for undergraduate
students. 4.4 Record generation speed where timing data is available.
4.5 Consider the clarity and usefulness of the generated output.

### Step 5: Evaluate and Document the Results

5.1 Compare the outputs using the defined evaluation criteria. 5.2
Identify the strengths and limitations of each prompting approach. 5.3
Document the generated summaries under their corresponding prompts. 5.4
Use the observations to determine which prompting approach is most
suitable for the summarization task.

## Sample Article

### Article: The Importance of Artificial Intelligence in Education

Artificial Intelligence (AI) has become one of the most significant
technological advancements of the 21st century. It is transforming
various industries, including healthcare, finance, transportation, and
education. In the education sector, AI helps improve learning
experiences by providing personalized education, automating
administrative tasks, and supporting teachers with valuable insights.

One of the biggest advantages of AI in education is personalized
learning. Every student learns at a different pace and has unique
strengths and weaknesses. AI-powered learning platforms can analyze a
student's performance and recommend customized learning materials,
quizzes, and exercises. This enables students to focus on areas where
they need improvement while progressing quickly through topics they
already understand.

AI also helps teachers by reducing repetitive administrative work. Tasks
such as grading assignments, tracking attendance, and preparing reports
can be automated, allowing teachers to spend more time interacting with
students and improving classroom engagement. Virtual teaching assistants
and AI chatbots are available around the clock to answer students'
questions, making learning more accessible.

Another important application of AI is in language learning. AI-powered
translation tools, speech recognition systems, and grammar correction
software help students improve their communication skills. Students can
receive instant feedback on pronunciation, writing, and vocabulary,
making language learning more effective.

Despite its many benefits, AI also presents certain challenges. Data
privacy is a major concern because AI systems often collect and analyze
personal information about students. Educational institutions must
ensure that student data is stored securely and used responsibly.
Additionally, excessive dependence on AI may reduce critical thinking
and human interaction if not balanced with traditional teaching methods.

The future of AI in education looks promising. Emerging technologies
such as intelligent tutoring systems, virtual reality, and adaptive
learning platforms are expected to make education more interactive and
engaging. However, AI should be viewed as a tool that supports teachers
rather than replacing them. Human creativity, empathy, and mentorship
remain essential elements of quality education.

In conclusion, Artificial Intelligence is reshaping education by making
learning more personalized, efficient, and accessible. While challenges
related to privacy and ethical use must be addressed, the responsible
implementation of AI has the potential to improve educational outcomes
for students worldwide.

## Prompts and Generated Results

### PROMPT 1

**Prompt:**

> Summarize the following article in a few sentences.

**Generated Result:**

Artificial Intelligence is transforming education by enabling
personalized learning, automating administrative tasks for teachers, and
supporting language acquisition through instant feedback. While it
enhances accessibility and efficiency, challenges such as data privacy
concerns and the risk of over-reliance must be managed. Ultimately, AI
serves as a powerful supportive tool that works alongside human
educators to improve global educational outcomes without replacing the
vital role of human mentorship.

### PROMPT 2

**Prompt:**

> Executive Summary: The Role of AI in Education

**Generated Result:**

Artificial Intelligence is emerging as a transformational force in the
education sector, offering tailored learning experiences and
administrative support while raising critical questions around privacy
and pedagogy.

#### Key Benefits & Applications

-   **Personalized Learning:** AI platforms analyze individual student
    performance data to deliver customized coursework, allowing learners
    to focus on specific growth areas while accelerating through
    mastered material.
-   **Administrative Efficiency:** Automation handles routine,
    time-consuming tasks like grading, attendance tracking, and
    reporting. This frees teachers to focus more on direct student
    interaction and classroom engagement.
-   **24/7 Support:** AI chatbots and virtual assistants provide
    round-the-clock answers to student queries, boosting accessibility.
-   **Enhanced Language Acquisition:** Speech recognition, real-time
    grammar checks, and translation tools provide instant feedback on
    pronunciation and writing.

#### Challenges & Ethical Considerations

-   **Data Privacy:** Because AI systems gather and process personal
    information, institutions must enforce strict data security and
    ethical use policies.
-   **Over-Reliance:** Unchecked reliance on AI tools risks undermining
    critical thinking skills and diminishing meaningful human
    interaction.

#### The Editorial Takeaway

The future of education will likely feature deeper integration of
immersive, adaptive AI tools. However, AI must serve as an auxiliary
tool to empower educators, not replace them. Core elements of effective
education---human empathy, creativity, and mentorship---remain
irreplaceable.

### PROMPT 3

**Prompt:**

> You are a technical writer preparing study notes for first-year
> engineering students. Summarize the following article using simple
> language so beginners can understand it easily.

**Generated Result:**

### Study Notes: Importance of Artificial Intelligence in Education

#### Overview

Artificial Intelligence (AI) is transforming various modern industries,
including healthcare, finance, transportation, and education. Within the
education sector, AI improves learning experiences by offering
personalized instruction, automating routine tasks, and providing
teachers with valuable data insights.

#### Key Applications & Benefits

-   **Personalized Learning:** AI platforms analyze student performance
    to deliver customized exercises, quizzes, and learning materials.
    This helps students strengthen weak areas while progressing rapidly
    through concepts they already know.
-   **Task Automation for Educators:** AI handles repetitive
    administrative work---such as grading assignments, tracking
    attendance, and generating reports. This frees up time for teachers
    to focus on classroom interaction and student engagement.
-   **24/7 Learning Support:** AI chatbots and virtual teaching
    assistants are available around the clock to answer student
    questions, making learning materials accessible anytime.
-   **Language & Communication Improvement:** Tools powered by AI---such
    as speech recognition, translation, and grammar correctors---give
    real-time feedback on writing and pronunciation to build strong
    communication skills.

#### Challenges & Concerns

-   **Data Privacy:** AI systems process and store personal information
    about students. Educational institutions must implement strong
    security measures to handle student data safely and ethically.
-   **Risk of Over-reliance:** Depending too heavily on AI can reduce
    critical thinking skills and human interaction if balanced
    traditional teaching methods are not maintained.

#### Future Outlook

-   **Emerging Innovations:** Technologies such as adaptive learning
    platforms, virtual reality, and intelligent tutoring systems will
    make future education more interactive and immersive.
-   **Teacher Support, Not Replacement:** AI serves as a tool to assist
    educators. Human empathy, creativity, and mentorship remain
    essential to quality education and cannot be replaced by machines.

**Key Takeaway:** When deployed responsibly with strong privacy
standards, AI makes education more personalized, efficient, and
accessible worldwide while enhancing the teacher's role rather than
replacing it.

### PROMPT 4

**Prompt:**

> You are a technical writer preparing study notes for first-year
> engineering students. Summarize the following article in exactly 100
> words, using simple English, avoiding technical jargon, and include
> only the three most important points.

**Generated Result:**

Artificial Intelligence is transforming modern education by improving
learning experiences for students everywhere. Here are the three most
important points from the article:

-   **Personalized Learning:** AI platforms analyze performance to
    customize educational materials, exercises, and quizzes, matching
    each student's unique learning speed and individual needs.
-   **Teacher Support:** AI reduces routine workloads by automating
    tasks like grading assignments, freeing teachers to spend
    significantly more time directly interacting with students.
-   **Privacy and Overreliance:** Schools must protect sensitive student
    data privacy and carefully avoid excessive dependence on technology.

Ultimately, AI serves as a tool supporting teachers rather than
replacing human empathy and mentorship.

### PROMPT 5

**Prompt:**

> You are a technical writer preparing study notes for first-year
> engineering students. Summarize the following article in exactly 100
> words using simple English. Present the output in the following
> format:
>
> Title\
> Summary\
> Key Points (3 Bullet Points)

**Generated Result:**

#### Title

**Artificial Intelligence in Education**

#### Summary

Artificial Intelligence is transforming global education by
personalizing learning, automating administrative tasks, and enhancing
language acquisition. Adaptive platforms cater to individual student
needs, while automated grading and virtual assistants save valuable time
for educators. However, implementation faces challenges concerning
student data privacy and potential reductions in critical thinking
skills. Emerging technologies promise even greater engagement, but AI
remains a supportive tool designed to assist rather than replace
essential human mentorship.

#### Key Points

-   AI customizes student learning and automates routine teaching
    workloads.
-   Data privacy risks and overreliance represent key implementation
    challenges.
-   Technology supports educators effectively.

## Result

The experiment shows that the quality of an AI-generated summary depends strongly on how the prompt is written. A simple prompt produces a short and general summary, while structured and role-based prompts produce more organized and student-friendly results.

- **Prompt 1 – Simple summarization:** Produced a concise summary covering the main benefits and challenges of AI in education.
- **Prompt 2 – Executive summary:** Produced a well-structured output with clear sections for benefits, applications, challenges, and the overall takeaway.
- **Prompt 3 – Role-based prompting:** Produced detailed study notes in simple language, making the content easier for first-year engineering students to understand.
- **Prompt 4 – Constrained prompting:** Produced a focused summary by restricting the output to three important points and simple English.
- **Prompt 5 – Structured + constrained prompting:** Produced a clearly formatted answer with a title, summary, and three key points.

### Overall Observation

Among the tested prompts, **role-based and structured prompts with clear output constraints** produced more organized and learner-oriented summaries. However, the provided experiment document contains generated examples from **ChatGPT only**; it does not provide corresponding outputs or measurements for Gemini, Claude, or Copilot. Therefore, a factual comparison of the AI platforms, including speed and user experience, cannot be concluded from the supplied data alone.

The experiment demonstrates that giving the AI a clear role, target audience, format, and length requirement can improve the usefulness and consistency of text summarization.
