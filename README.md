# Week 4 : April 10, 2020

# Labs-Sprint-Challenge-2.1- Follow design pattern and architectural guidelines

This challenge allows you to practice the concepts and techniques learned over the past week and apply them by providing answers to questions related to following architectural and design decisions of your Labs product.

In your challenge this week, you will demonstrate understanding over these topics by responding to 2 prompts

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Journal Entry.**

You are not allowed to collaborate during the Journal Entry. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in team planning and product vision.

We have allocated time on your schedule to ensure that you get this done at the end of each sprint.

- For Full Time Students: Please submit your work on this journal entry before 12pm PST every Friday.
- For Part Time Students: Please submit your work on this journal entry before the end of your B-Week Thursday class period.

## Prompt 1

For this response, please focus on your individual contributions.

**Engineers:**

Describe your contribution to your team's goals this sprint.

- How did you ensure that you implemented the designer's vision accurately?
  * We checked in with our UX designer often to get tips on how she wanted certain actions and effects to be applied. She herself checked with the stakeholder to see if her designs was along the lines of his vision. 
  
- What were the biggest challenges you faced this sprint?
    * We encountered a major issue as we ended our week. The data model and inputs that was approved with our stakeholder are not uniformed. The thing is that we assumed that since he has experience in our Lambda program that he is capable of coming up with data models and being visual on the end product, but the truth is, even if a person does, they still need assistance with people who have more experience in those different features. So we have arranged to meet with so that we would not fall victims of assuming information and giving him an end product that he would find not satisfactory. 

- Describe the data layer of your application. (Feel free to pick a single model and break down the required fields for that resource. Are there any relationships? e.g. 1 to many, many to 1, etc.).

#### Board Member - User creation

`{   
    website_address: "",
    street_address: "",
    email: "",  **relation to userID : one to one
    phone: ""
}
`

- Describe your product's application structure and code patterns. Why or why not is your team using a linter? If applicable, describe the structure of your API.

 * My team mates are using Linter, I'm not since I've noticed it formats already formatted files, and files I don't even touch. I'm still learning how to play around with the settings, so for now it's turned off. 

 * The structure of our API at first was based off how React Hook Forms and Antd  nested data format, but once we removed the React Hook Forms, it would output the correct properties that the backend from Apollo had auto generated. 

**UX designers:**

Describe how you communicated the design direction to your team.

- Describe the relationship with your stakeholder.
- If you started your design system, describe how you selected key styles including colors and typography. How did the target users influence your visual design decisions?

**Data scientists:**

Describe your process of working with the engineering and design teams.

- How did design/engineering help guide the solution to the product's data science problems?

## Prompt 2 - To be completed if your team deviated from your plan

Now that you've been through or are nearly completing a full product release cycle, we'd like to know how your plan changed.

* We discussed that we probably bit off more than we could chew in our first release. We were exploring the possibility of spliting it up and adding it to our second release since we don't have as much going on there. 
The second time, it's not that we did, but we talked about considering going with REST API instead of prisma and apollo to help us meet MVP. 

**Please fill out if, during this release canvas, you deviated from your original plan**

[Here is a link to the **Diff Entry**](DIFFENTRY.md)

## Submitting your work

Please submit a link to your journal entry for this sprint, in the Sprint Retrospective Form. This is to be done every _Friday before Noon_ -- for Full Time -- and before the end of your 2nd '5th' day -- for Part Time -- to be counted as a submission for that sprint.

## Rubric & Samples

[Here is a link to the rubric](https://www.notion.so/lambdaschool/2-1-Rubric-Follow-design-pattern-and-architectural-guidelines-9223a4fd514f4499bef64b9bdb255e85) that will be used to assess your answers to the prompts. _Use this as a guide_ as you craft your responses.

[Here is a link to a sample submission](https://www.notion.so/lambdaschool/2-1-Contribution-Entry-Following-Design-Patterns-and-Architectural-Guidelines-99948cbf411643b1bce58568785e87a4) that you can use for inspiration.
