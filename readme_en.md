# AI Portfolio Submission Guide

> This portfolio is designed to assess your AI utilization skills.  
> Please include **at least 2** of the following 7 items in your submission.

## ⚠️ Required Guidelines

### 🔒 Security Compliance
- Ensure no **confidential data** or **source code** from previous employers is included
- Use **public datasets** or **mock-up data**

### 📊 Contribution Disclosure
- Clearly specify your role and the extent of generative AI tool usage during the project
- Example: `Architecture design 100%, Code implementation 50% + AI assistance 50%`

### 🔍 Problem-Solving Process
- Documents that include **data preprocessing**, **model selection rationale**, and **troubleshooting process** are preferred over simple deliverables

### ▶️ Executability
- Attach a **GitHub link** or **demo URL** where the code can be verified



## 📋 Items to Include (Select 2 or more)

### 1. Problems Solved or Automation Cases Using AI

**Include:**
- What was the situation/problem
- How AI was utilized
- How results were improved
- Before/after comparison or improvement metrics

**Example:**
```markdown
## Problem Situation
- Manually classifying over 100 customer inquiries per week took an average of 2 hours

## AI Utilization Method
- Built an automated classification system using Claude API
- Improved category classification accuracy through prompt engineering

## Improvement Results
- Processing time: 2 hours → 10 minutes (92% reduction)
- Classification accuracy: 95%
```

---

### 2. Actual Prompts or Prompt Templates Used

**Include:**
- Key prompt examples
- Prompt structure
- Prompt improvement process (initial draft → revised)

**Example:**
```markdown
## Prompt Template

### Initial Draft
"Refactor this code"

### Improved Version
"""
Please refactor the following Python code:
- Goal: Improve readability and optimize performance
- Constraints: Use Python 3.9+ syntax, include type hints
- Style: Follow PEP 8

[Code]
"""

## Improvement Effect
- Response accuracy 70% → 95%
- Increased rate of obtaining desired format responses
```

---

### 3. AI-Generated Initial Output vs. Self-Revised Final Output

**Include:**
- Before/after refactoring of generated code
- Automation script draft vs. actual delivered code
- Parts AI got wrong and the correction process

**Example:**
```markdown
## AI-Generated Draft
[Screenshot or code block of AI-generated code]

## Issues Identified
1. Lack of error handling
2. Potential memory leak
3. Inefficient algorithm usage

## Final Revised Version
[Revised code]

## Key Modifications
- Added try-except statements
- Utilized context managers
- Optimized from O(n²) → O(n log n)
```

---

### 4. Cases of Integrating AI into Development Workflow

**Include:**
- GitHub Actions + AI-based reports
- AI-based code review system
- Automation pipelines for repetitive tasks

**Example:**
```markdown
## Integration Case: GitHub Actions + AI Code Review

### Structure
1. Automatically call Claude API when PR is created
2. Analyze changes and generate review comments
3. Automatically post comments via GitHub API

### Benefits
- 50% reduction in code review time
- Maintained consistent code quality
- Reduced review burden on team members

[GitHub Actions Workflow file link]
```

---

### 5. Experience Encountering and Resolving AI Limitations

**Include:**
- Hallucination issues
- Context insufficiency problems
- Incorrect structure/bug generation
- How these were verified/adjusted

**Example:**
```markdown
## Problem Situation
Claude suggested a non-existent library function

## Resolution Process
1. Built a verification process for AI responses
2. Added automatic official documentation reference system
3. Automated test code generation and execution

## Results
- 80% reduction in hallucination problem occurrence
- Reliable code generation
```

---

### 6. Prototype Development Cases Using AI

**Include:**
- Prototypes quickly built within 24-48 hours
- Which parts AI assisted with
- Materials demonstrating structuring ability

**Example:**
```markdown
## Prototype: AI-Based Schedule Management App

### Development Period
48 hours (2 days)

### AI Utilization Scope
- UI component draft: Claude generated (80%) + manual adjustment (20%)
- API endpoint design: Claude suggested → reviewed and modified
- Test code: GitHub Copilot utilized (60%)

### Personal Contribution
- Architecture design: 100%
- Business logic implementation: 70%
- Integration and deployment: 100%

[Demo Link] | [GitHub Repository]
```

---

### 7. LLM-Based Feature Development Experience

**Include:**
- AI API integration experience (OpenAI, Google, AWS, Naver, etc.)
- Simple RAG search feature implementation (Optional)
- User input processing / token control / prompt chain construction
- Cost management experience

**Example:**
```markdown
## Project: Internal Document Search Chatbot

### Tech Stack
- LLM: OpenAI GPT-4 API
- Vector DB: Pinecone
- Framework: LangChain

### Key Implementation Details

#### 1. RAG Search Implementation
# Document embedding and storage
[Code]

# Search and answer generation
[Code]

#### 2. Token Control
- Input token limit: Maximum 3000 tokens
- Response length control: max_tokens=500
- Context window management: Sliding window approach

#### 3. Prompt Chain
[Document Search] → [Context Summarization] → [Answer Generation] → [Answer Verification]

#### 4. Cost Management
- Monthly budget: $200
- 30% reduction in API calls through caching strategy
- Actual cost: $150/month (25% savings)

### Outcomes
- Document search time: 5 minutes → 30 seconds
- User satisfaction: 4.5/5.0
- ROI: Equivalent to $2,000/month in saved work hours

```


## 📄 Submission Format

- Markdown format (uploaded to GitHub)
- Screenshots and code blocks may be included
- GIFs and video links may be added
- Structure for readability

## ➕ Optional Items (Bonus points if included)

- Part of a project
- Automation tool links
- Additional GitHub repositories
- Live demo links


## 💡 Writing Tips

> Show how you utilize AI in actual work and how you improve those results!
