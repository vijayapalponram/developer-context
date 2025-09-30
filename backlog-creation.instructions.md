# Feature Workflow Instructions

Go over the below steps and complete all tasks specified in each step.

---

## Step 1: Analyse the Feature

- Understand the feature and ask any questions to the author.
- List down the dependencies for the feature.
- Identify any risks associated with the feature.
- Get confirmation from the author on the understanding by asking to click the button **'Proceed'** / **'Analyze further'**.
- If the author clicked **'Analyze further'**, ask what is missing. Based on the input, start over from Step 1.
- If the author clicked **'Proceed'**, save the analyzed feature details in a readme file:  
  `/doc/feature-[feature-title].md`  
  Then start Step 2 automatically.

---

## Step 2: Create High-Level Stories

- Follow the user story creation instructions to split the feature into user stories.
- Once user stories are created, check with the author by asking to click the button **'Proceed'** / **'Add more'**.
- If the author clicked **'Add more'**, ask what is missing. Based on the input, start over from Step 2.
- If the author clicked **'Proceed'**, then start Step 3 automatically.

---

## Step 3: Review the Stories

- Pick a story from the list of stories in order.
- Update the review status as **'In Progress'** in the respective story readme file.
- Before asking the author to review, ensure the status is updated as **'In Progress'**.
- Ask the author to review each story one by one and get confirmation by clicking **'Review Completed'** / **'Refine further'**.
- If the author clicked **'Refine further'**, ask what is missing. Modify the story based on input and continue refinement until the author clicks **'Review Completed'**.
- Once the author clicks **'Review Completed'**, update the review status as **'Completed'** in the respective story readme file.
- Repeat Step 3 until all stories are reviewed.
- Once all stories are completed, start Step 4 automatically.

---

## Step 4: Finish the Backlog Creation

- Create a CSV file to include all stories in a single file with proper table format.
- The CSV should include the following columns:

  - **Title**: [Story Title]  
  - **Description**: [Brief description of the story]  
  - **Acceptance Criteria**:
    - [Criterion 1]
    - [Criterion 2]
    - [Criterion 3]
  - **Priority**: [High/Medium/Low]  
  - **Estimation**: [Story points or time estimate]  
  - **Priority Order**: [1/2/3]  
  - **Review Status**: [Not Started/In Progress/Completed]  
  - **Status**: [Not Started/In Progress/Completed/Blocked]

---

## Step 5: Share the Feedback

- Share your experience on how the instructions helped in generating responses.
- Suggest improvement areas in the instructions.
- Describe how the author provided inputs.
- Give a rating (1–5) for the current session based on your feedback:
  - **1** = Low  
  - **5** = High


