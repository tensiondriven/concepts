# Concept Processing Prompt

## Task
Review each file in `inbox/` and convert viable concepts into GitHub Projects with detailed project cards.

## Process for Each Inbox Item

1. **Read the concept note**
2. **Assess viability** - Is this a complete enough idea for a project?
3. **If viable:**
   - Create new GitHub repository 
   - Create corresponding GitHub Project
   - Break concept into detailed project cards covering:
     - Core requirements
     - Technical approach 
     - Market analysis (if applicable)
     - Implementation roadmap
     - TODO section (requirements clarification, not build tasks)
     - Estimated costs
     - Complexity assessment
     - Risk analysis
     - Any other relevant aspects
   - Move processed file to `processed/` folder with commit message linking to created project/cards
4. **If not viable:**
   - Leave in inbox with comment about what's needed

## Project Card Structure Template

Each concept should generate comprehensive project cards that include:

### Core Requirements Card
- Primary features and functionality
- User experience goals
- Success criteria

### Technical Approach Card
- Architecture decisions
- Technology stack considerations
- Integration requirements

### Market Analysis Card (if applicable)
- Target audience
- Competitive landscape
- Market opportunity

### Implementation Roadmap Card
- Development phases
- Key milestones
- Dependencies

### TODO Card (Requirements Clarification)
- Questions to resolve before development
- Missing information or specifications
- Stakeholder decisions needed

### Cost Estimation Card
- Development costs (time/money)
- Infrastructure costs
- Operational costs
- Third-party service costs

### Complexity Assessment Card
- Technical complexity (1-5 scale)
- Business complexity
- Integration complexity
- Key challenging areas

### Risk Analysis Card
- Technical risks
- Market risks
- Resource risks
- Mitigation strategies

## GitHub CLI Commands
Use `gh project create` to create projects and appropriate commands to add cards to projects.

## Repository Naming
Use descriptive, lowercase, hyphenated names that clearly indicate the project purpose.

## Git Workflow
After processing each item:
1. Commit with message: "Process [concept-name]: moved to processed/"
2. Include links to generated GitHub project and cards in commit message
3. Reference any additional resources created

## Completion
After processing all inbox items, provide summary of:
- Projects created with links
- Items left in inbox (with reasons)  
- Next steps for each project