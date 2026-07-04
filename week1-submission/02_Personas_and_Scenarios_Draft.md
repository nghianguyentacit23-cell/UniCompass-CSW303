# Personas and Scenarios Draft

## Persona 1: First-Year Student

| Field | Description |
|---|---|
| Name | Minh Anh |
| Profile | First-year Software Engineering student |
| Goals | Understand which courses to take first, avoid incorrect registration, keep study progress on track, and feel less confused during course registration. |
| Pains | Does not fully understand prerequisite rules, finds curriculum documents difficult to read, receives inconsistent advice from classmates or senior students, and feels anxious near registration deadlines. |
| Current Workflow | Reads the curriculum PDF, checks class group chats, asks senior students, waits for academic advisor announcements, and makes decisions close to the deadline. |
| Tech Comfort | Comfortable with learning apps, chat tools, calendars, and simple dashboards, but does not want to read long academic documents. |
| Key Quotes | "I just want to know what I should register for next semester without making a mistake." |

## Persona 2: Career-Oriented Student

| Field | Description |
|---|---|
| Name | Gia Huy |
| Profile | Third-year student interested in AI and Data-related career paths |
| Goals | Choose courses that support career goals, avoid being blocked by missing prerequisites, maintain a competitive GPA, and prepare for internship opportunities. |
| Pains | Worries that failing one course may affect later courses, spends too much time comparing study plans, manually calculates GPA possibilities, and feels uncertain about whether a plan is realistic. |
| Current Workflow | Uses spreadsheets, reads curriculum documents, asks students from previous cohorts, compares different schedules manually, and checks GPA requirements for scholarships or internships. |
| Tech Comfort | Very comfortable with digital tools, prefers clear dashboards, wants fast recommendations, and still expects understandable explanations. |
| Key Quotes | "I need to know whether delaying one course will affect my internship plan." |

# Scenario 1: Proactive Semester Planning

| Field | Description |
|---|---|
| Trigger | The student is preparing for course registration for a new semester. |
| Actor | First-year student or any student planning the next semester. |
| Preconditions | The student has basic academic information in the system, including major, current semester, completed courses, and recent results. |
| Main Steps | 1. The student opens UniCompass and chooses semester planning. 2. The system shows the student's current academic status in a simple overview. 3. The student selects the desired workload, such as light, balanced, or ambitious. 4. The system suggests suitable courses for the next semester. 5. The system explains each suggestion using short reasons such as "suitable for your current progress", "recommended to avoid delay", or "matches your career direction". 6. The student reviews the plan and saves a temporary semester plan. |
| Alternate Steps | If the student selects a course that may not be suitable, the system shows a clear warning and suggests another option. |
| Success Criteria | The student receives a clear and realistic course list for the next semester and feels more confident before registration. |

# Scenario 2: What-If Failure Simulation

| Field | Description |
|---|---|
| Trigger | The student is worried about failing a current course or has received a low midterm result. |
| Actor | Student who wants to understand possible consequences before making a decision. |
| Preconditions | The student has a current study plan and a list of ongoing courses. |
| Main Steps | 1. The student opens the option "What if I fail this course?". 2. The student selects the course they are worried about. 3. The system shows possible effects, including later courses that may be affected, credits that may need to be retaken, possible delay, and GPA impact. 4. The system presents practical response options, such as retaking the course soon, reducing workload in the next semester, or adjusting the graduation plan. 5. The student compares the current plan with the adjusted option. |
| Alternate Steps | If the selected course has low impact on later progress, the system explains that the risk is limited and shows why the student can still remain on track. |
| Success Criteria | The student understands the possible consequences of failing a course and has at least one realistic recovery option. |

# Scenario 3: GPA Feasibility Check

| Field | Description |
|---|---|
| Trigger | The student wants to know whether a target GPA is still achievable. |
| Actor | Student aiming for scholarship, internship, honors graduation, or personal academic improvement. |
| Preconditions | The student has current GPA information, completed credits, remaining credits, and a target GPA. |
| Main Steps | 1. The student enters or selects a target GPA. 2. The system shows the current GPA, the gap to the target, and the average performance needed in future courses. 3. The system labels the goal as realistic, challenging but possible, or unrealistic. 4. The system gives simple suggestions, such as which courses need more attention, why failing a course would be risky, or whether a more realistic target should be considered. |
| Alternate Steps | If the goal is too high, the system suggests a more realistic target and explains it using easy-to-understand numbers. |
| Success Criteria | The student knows whether the target GPA is achievable and understands what level of performance is needed from now on. |

