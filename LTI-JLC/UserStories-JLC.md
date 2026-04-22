# UserStories-JLC

## 1. User Stories

### 🧩 US-001 --- Candidate applies to a job

**As a** candidate\
**I want to** apply to a job posting\
**So that** I can be considered for a position

**Description**\
Candidates should be able to browse job listings and submit applications
including CV and relevant data.

**Acceptance Criteria (BDD)**\
- Given I am on a job listing page\
When I click "Apply"\
Then I can submit my application with CV

-   Given I submit an application\
    When the submission is successful\
    Then I receive a confirmation

-   Given I submit incomplete data\
    When I try to submit\
    Then I see validation errors

**INVEST Evaluation**\
✔ Independent\
✔ Negotiable\
✔ Valuable\
✔ Estimable\
✔ Small\
✔ Testable

------------------------------------------------------------------------

### 🧩 US-002 --- Recruiter creates a job position

**As a** recruiter\
**I want to** create a job position\
**So that** I can publish job offers

**Acceptance Criteria**\
- Create position with title, description, requirements\
- Position is stored in DB\
- Position appears in listings

------------------------------------------------------------------------

### 🧩 US-003 --- AI-assisted candidate ranking

**As a** recruiter\
**I want to** receive AI-based candidate ranking\
**So that** I can prioritize best candidates faster

**Acceptance Criteria** - AI ranks candidates based on CV + interviews\
- Ranking is visible in UI\
- Scores are explainable

------------------------------------------------------------------------

## 2. Product Backlog (Prioritized)

  ID       User Story            Value       Effort   Priority
  -------- --------------------- ----------- -------- ----------
  US-001   Apply to job          High        Medium   P1
  US-002   Create job position   High        Medium   P1
  US-003   AI ranking            Very High   High     P2

------------------------------------------------------------------------

## 3. Selected User Story

US-001 --- Candidate applies to a job

------------------------------------------------------------------------

## 4. Work Tickets

### T-001 --- Backend API

-   Create Application model
-   Validate input
-   Store CV
-   Persist in DB Estimation: 5 SP

### T-002 --- Frontend Form

-   Build UI
-   File upload
-   API integration Estimation: 5 SP

### T-003 --- Validation

-   Input validation
-   Error handling Estimation: 3 SP

### T-004 --- Notifications

-   Send confirmation email Estimation: 3 SP

### T-005 --- Testing

-   Unit + integration tests Estimation: 5 SP

------------------------------------------------------------------------

## 5. Total Estimation

Total: 21 Story Points
