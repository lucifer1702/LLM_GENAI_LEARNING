# WRITER.PY

# Overview:

1. Imports necessary libraries and sets up environment variables.
2. Defines agents (Content Planner, Content Writer, Editor) with specific roles, goals, backstories, and delegation settings.
3. Creates tasks for each agent with descriptions, expected outputs, and assigned agents.
4. Sets up a Crew with the defined agents and tasks.
5. Initiates the crew to kick off the content creation process based on the provided topic.
6. Displays the result in Markdown format.

### Documentation Outline:

#### Agents:

1. **Content Planner:**

   - Role: Content planner
   - Goal: Create an accurate blog about the specified topic in a detailed fashion
   - Backstory: Details the role and responsibilities of the Content Planner
   - Delegation: Not allowed
2. **Content Writer:**

   - Role: Content Writer
   - Goal: Write insightful and factually accurate opinion piece about the topic
   - Backstory: Details the role and responsibilities of the Content Writer
   - Delegation: Not allowed
3. **Editor:**

   - Role: Editor
   - Goal: Edit a given blog post to align with the organization's writing style
   - Backstory: Details the role and responsibilities of the Editor
   - Delegation: Not allowed

#### Tasks:

1. **Content Planning Task:**

   - Description: Outlines the steps for content planning
   - Expected Output: Comprehensive content plan document
   - Assigned Agent: Content Planner
2. **Content Writing Task:**

   - Description: Outlines the steps for content writing
   - Expected Output: Well-written blog post in markdown format
   - Assigned Agent: Content Writer
3. **Editing Task:**

   - Description: Outlines the steps for editing the blog post
   - Expected Output: Well-written blog post in markdown format
   - Assigned Agent: Editor

#### Crew:

- **Crew Setup:**
  - Agents: Content Planner, Content Writer, Editor
  - Tasks: Content Planning, Content Writing, Editing
  - Verbose Level: 2

### Next Steps:

- Ensure all necessary libraries are installed (`crewai`, `dotenv`, `IPython`).
- Review and customize the agents' roles, goals, and backstories as needed.
- Modify the tasks' descriptions and expected outputs to align with specific requirements.
- Execute the script to kick off the content creation process for the specified topic.
