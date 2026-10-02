Customer Success AI Assistant
A practical experiment in AI-assisted customer support

Project status: Learning project / prototype

The problem

Customer Success Managers often receive customer messages containing several pieces of information at once. Before responding, a CSM may need to determine the customer's primary issue, urgency, emotional tone, missing information, possible causes, and appropriate next steps.

I wanted to explore whether AI could help organize this initial analysis while keeping the CSM responsible for judgment and the customer relationship.

The workflow

Customer message

↓

Identify the main issue

↓

Categorize the issue

↓

Assess urgency and customer tone

↓

Check whether enough context is available

↓

If information is missing, identify what needs to be clarified

↓

If sufficient information is available, identify possible resolutions

↓

Draft an appropriate customer response

↓

Recommend next steps

↓

Create a concise CRM-style note

Context-gathering logic

Before suggesting a resolution, the AI checks for relevant information such as:

Technical/access issues
Service outages or intermittent problems
Application version
Training attendance and understanding
Reported obstacles, errors, or glitches
Product/feature fit for the customer's business
Configuration or customization needs
User experience and usability
Differences in users' technical familiarity

The AI should not assume that every question is relevant to every customer. It should identify the information that is actually needed based on the customer's situation.

Human judgment

The AI is intended to assist the CSM rather than make the final decision.

If the available information is insufficient, the workflow should identify what is missing rather than confidently inventing an explanation or resolution.

The CSM remains responsible for reviewing recommendations, communicating with the customer, and deciding what action to take.

Example
Customer message

We've been using the platform for two months, but only half of our team is actually using it. We've tried sending reminders, but adoption hasn't improved. Can someone help us figure out what we're doing wrong?

AI analysis

Primary issue:
Low user adoption.

Category:
Training / adoption.

Urgency:
Medium. The customer is concerned about the value of their investment, but there is no indication of a critical service interruption.

Customer tone:
Concerned and frustrated, but still seeking help constructively.

Information to clarify before recommending a resolution:

Did all users attend the original training?
Do users understand the relevant workflows?
Are users having difficulty navigating the platform?
Are there specific features they are avoiding or unable to use?
Are there differences in technical familiarity among users?

Potential next steps:

Identify whether the problem is primarily training, usability, product fit, or user adoption.
Gather targeted information from the customer rather than asking every possible diagnostic question.
Review relevant usage information if available.
Determine whether additional training or a targeted walkthrough would help.
Follow up after the intervention to determine whether adoption improves.

Suggested response:

Thanks for reaching out. It sounds like the main challenge is getting broader adoption across your team, and we'd be happy to help. Before recommending the best next step, I'd like to understand a little more about where users are getting stuck. Did everyone attend the original training, and are there particular parts of the platform that users are having difficulty with or avoiding? Once we understand the main barrier, we can determine whether additional training, workflow guidance, or another approach would be most helpful.

CRM-style note:

Customer reports low platform adoption after two months despite internal reminders. Customer is concerned about team engagement and requested assistance. Further information needed regarding training completion, usability, and specific adoption barriers.

What I learned

This experiment helped me understand that using AI effectively is not simply about asking an AI tool a question.

The quality of the result depends on how clearly the problem is defined, what context is provided, what information is required before making a recommendation, and where human judgment remains necessary.

I also learned how conditional logic can be used to determine which information is relevant to different customer situations, rather than applying the same checklist to every customer.

Next steps:
I plan to continue experimenting with AI and automation tools to determine how this type of workflow could eventually connect with customer-success systems and reduce repetitive work.
