# 🚀 Der ultimative Leitfaden: Professionelles Coding mit KI

**Ein praxisorientierter Guide für effektive KI-gestützte Softwareentwicklung**

---

## 📚 Inhaltsverzeichnis

1. [Grundlagen & Mindset](#1-grundlagen--mindset)
2. [Session-Setup & Kontext](#2-session-setup--kontext)
3. [Effektive Kommunikation](#3-effektive-kommunikation)
4. [Entwicklungsprozess](#4-entwicklungsprozess)
5. [Code-Qualität & Review](#5-code-qualität--review)
6. [Testing & Debugging](#6-testing--debugging)
7. [Security & Performance](#7-security--performance)
8. [Wartung & Dokumentation](#8-wartung--dokumentation)
9. [Anti-Patterns & Fallstricke](#9-anti-patterns--fallstricke)
10. [Workflow-Templates](#10-workflow-templates)

---

## 1. Grundlagen & Mindset

### 1.1 Die richtige Erwartungshaltung

**KI ist kein magischer Code-Generator, sondern:**

- 🤝 Ein intelligenter Pair-Programming-Partner
- 🔍 Ein Beschleuniger für Routineaufgaben
- 💡 Ein Brainstorming-Tool für Lösungsansätze
- 📚 Eine On-Demand-Dokumentation

**KI ist NICHT:**

- ❌ Ein Ersatz für Verständnis und Expertise
- ❌ Unfehlbar oder allwissend
- ❌ Bewusst über Ihren spezifischen Kontext
- ❌ Ein Ersatz für Testing und Code-Review

### 1.2 Erfolgsformel

```
Effektives KI-Coding = 
    Klarer Kontext (30%)
  + Spezifische Anfragen (25%)
  + Iteratives Vorgehen (20%)
  + Kritisches Denken (15%)
  + Systematisches Testen (10%)
```

### 1.3 Die 3 goldenen Regeln

1. **Verstehe jeden Code** - Kein blindes Copy-Paste
2. **Vertraue, aber verifiziere** - Immer testen und reviewen
3. **Iteriere kontinuierlich** - Kleine Schritte, große Erfolge

---

## 2. Session-Setup & Kontext

### 2.1 Der perfekte Session-Start ⭐⭐⭐⭐⭐

**Template für maximale Effektivität:**

```markdown
You are an expert [LANGUAGE] developer specializing in [DOMAIN].

## Project Context
- **Project Type:** [e.g., REST API, Web App, CLI Tool]
- **Tech Stack:**
  - Language: [e.g., Python 3.11]
  - Framework: [e.g., FastAPI 0.104.1]
  - Database: [e.g., PostgreSQL 15]
  - ORM: [e.g., SQLAlchemy 2.0]
  - Testing: [e.g., pytest 7.4]
  
## Architecture
- Pattern: [e.g., Clean Architecture, MVC]
- Structure: [describe folder structure]
- Key principles: [e.g., SOLID, DRY]

## Standards & Constraints
- Code Style: [e.g., PEP 8, ESLint Airbnb]
- Python Version: 3.11+
- Performance: API responses < 200ms
- Security: OWASP Top 10 compliant
- Test Coverage: Minimum 80%

## Current Task
I'm implementing [SPECIFIC FEATURE]. 

## Code Quality Requirements
For every solution, please provide:
1. Complete, production-ready code (no placeholders)
2. Comprehensive error handling
3. Input validation
4. Security considerations
5. Performance optimization
6. Unit test examples
7. Clear documentation/comments

## Communication Preferences
- Be direct and concise
- Explain trade-offs and alternatives
- Point out potential issues proactively
- Reference official documentation when relevant
```

**Warum das funktioniert:**

- 🎯 Präzise Constraints reduzieren Halluzinationen
- 🔧 Tech Stack verhindert veraltete Lösungen
- 📋 Standards sichern Code-Qualität
- 🚀 Anforderungen sind explizit, nicht implizit

### 2.2 State Management während der Session ⭐⭐⭐⭐⭐

**KRITISCH:** KI hat kein persistentes Gedächtnis zwischen Messages!

#### Zu Beginn JEDER Session:

```markdown
## Current Code State

### File: user_service.py
[Vollständiger Code hier einfügen]

### File: user_model.py
[Vollständiger Code hier einfügen]

### Project Structure
project/
├── app/
│   ├── models/
│   │   └── user_model.py
│   ├── services/
│   │   └── user_service.py
│   └── routes/
│       └── auth_routes.py
└── tests/
    └── test_user_service.py

### Recent Changes
- Added JWT authentication (last session)
- Implemented password hashing with bcrypt
- Created user registration endpoint

### Current Issue
[Beschreibung des aktuellen Problems]
```

#### Während der Session:

**Alle 5-10 Messages:**

- ✅ Aktualisierte Code-Versionen erneut posten
- ✅ Zusammenfassung bisheriger Änderungen geben
- ✅ Explizit auf vorherige Lösungen referenzieren

**Beispiel:**

```
Based on the UserService class we created earlier [paste updated code],
I now need to add password reset functionality.
```

### 2.3 Kontext-Template für verschiedene Szenarien

#### Neues Feature implementieren:

```markdown
## Feature Request
**Feature:** [Name]
**Purpose:** [Why needed]
**User Story:** As a [user], I want to [action] so that [benefit]

## Technical Requirements
- Input: [what goes in]
- Output: [what comes out]
- Dependencies: [other components]
- Edge Cases: [special scenarios]

## Acceptance Criteria
1. [Criterion 1]
2. [Criterion 2]
3. [Criterion 3]
```

#### Bug Fixing:

```markdown
## Bug Report
**Expected Behavior:** [What should happen]
**Actual Behavior:** [What actually happens]
**Steps to Reproduce:**
1. [Step 1]
2. [Step 2]
3. [Step 3]

## Context
**Error Message:** 
[Vollständige Fehlermeldung]

**Stack Trace:**
[Vollständiger Stack Trace]

**Relevant Code:**
[Code der den Fehler verursacht]

**What I've Tried:**
- [Versuch 1] - Result: [...]
- [Versuch 2] - Result: [...]

**My Hypothesis:** [Was du denkst, wo das Problem liegt]
```

#### Code Review/Refactoring:

```markdown
## Code Review Request
**Goal:** [Improve performance/readability/security/etc.]
**Concerns:** [Specific worries]

**Current Implementation:**
[Code to review]

**Context:**
- This code runs [frequency/scenario]
- Current performance: [metrics if available]
- Pain points: [what's problematic]

**Please Review For:**
1. Code quality & best practices
2. Security vulnerabilities
3. Performance bottlenecks
4. Edge cases not handled
5. Potential refactoring opportunities
```

---

## 3. Effektive Kommunikation

### 3.1 Spezifität ist der Schlüssel ⭐⭐⭐⭐⭐

#### ❌ Vage Anfragen (ineffektiv):

```
"Create a login system"
"Fix this bug"
"Make it faster"
"Add authentication"
```

#### ✅ Spezifische Anfragen (hocheffektiv):

**Beispiel 1: Feature-Anfrage**

```markdown
Create a user login endpoint with these specifications:

**Endpoint Details:**
- Route: POST /api/v1/auth/login
- Content-Type: application/json

**Request Body:**
{
  "email": "user@example.com",
  "password": "SecurePass123!"
}

**Validation:**
- Email: Valid format, max 255 chars
- Password: 8-128 chars, required

**Business Logic:**
1. Find user by email (case-insensitive)
2. Verify password using bcrypt
3. Generate JWT token (expires in 24h)
4. Log login attempt (success/failure)
5. Implement rate limiting (5 attempts per 15 min)

**Success Response (200):**
{
  "token": "eyJhbGc...",
  "user": {
    "id": 123,
    "email": "user@example.com",
    "name": "John Doe"
  },
  "expires_at": "2024-11-20T10:30:00Z"
}

**Error Responses:**
- 400: Invalid request format
- 401: Invalid credentials
- 429: Too many attempts
- 500: Server error

**Security Requirements:**
- Password comparison in constant time
- No sensitive data in error messages
- Log security events
- HTTPS only (enforce in production)

**Performance:**
- Response time < 300ms
- Database query optimization
- Consider caching user lookup

**Testing:**
- Include 5 unit test cases
- Mock database calls
- Test rate limiting
```

**Beispiel 2: Bug Fix**

```markdown
Fix authentication bug in UserService.authenticate() method

**Current Code:**
def authenticate(self, email: str, password: str) -> Optional[User]:
    user = db.query(User).filter(User.email == email).first()
    if user and bcrypt.checkpw(password, user.password_hash):
        return user
    return None

**Issue:**
Getting AttributeError: 'NoneType' object has no attribute 'password_hash'

**Error Context:**
- Occurs when email doesn't exist in database
- Error happens at line: bcrypt.checkpw(password, user.password_hash)
- Expected: Should return None gracefully
- Actual: Crashes with AttributeError

**Environment:**
- Python 3.11
- bcrypt 4.0.1
- SQLAlchemy 2.0

**What I've Checked:**
✓ Database connection is working
✓ Query syntax is correct
✓ bcrypt is installed and working for valid users

**My Analysis:**
The issue is that when user is None (email not found), 
we still try to access user.password_hash. The if user 
check doesn't prevent the second part of the AND condition 
from being evaluated.

**Required Fix:**
- Handle None case before password check
- Maintain constant-time comparison (no timing attacks)
- Log failed attempts without exposing user existence
- Include proper type hints
- Add error handling for bcrypt exceptions
```

### 3.2 Die STAR-Methode für Anfragen

**S**ituation - **T**ask - **A**ction - **R**esult

```markdown
**Situation:** 
We have a user registration system that currently stores 
passwords in plain text (legacy code).

**Task:**
Migrate to secure password hashing using bcrypt while 
maintaining backward compatibility during transition.

**Action Required:**
1. Add bcrypt dependency
2. Create migration function to hash existing passwords
3. Update registration to hash new passwords
4. Modify login to check both formats during transition
5. Add flag to track migrated users

**Result Expected:**
- All passwords securely hashed
- No user login interruption
- Transition complete within 30 days
- Old password verification removed after migration

**Constraints:**
- Zero downtime required
- 100k existing users
- Must handle concurrent updates
- Rollback plan needed

Please provide step-by-step implementation with code.
```

### 3.3 Multi-Modal Kontext nutzen

#### Text + Screenshot:

```markdown
I'm getting this error when trying to log in:
[Screenshot des Errors]

Here's the code that's being called:
[Relevanter Code]

The error appears after clicking the login button.
User input: email="test@example.com", password="test123"

Stack trace:
[Stack Trace]

Database state: User exists in database, confirmed via direct query.
```

#### Text + Diagramm:

```markdown
Here's my current architecture:
[Diagramm oder ASCII-Darstellung]

┌──────────┐      ┌──────────────┐      ┌──────────┐
│  Client  │─────▶│   API Layer  │─────▶│ Database │
└──────────┘      └──────────────┘      └──────────┘
                         │
                         ▼
                  ┌─────────────┐
                  │ Auth Service│
                  └─────────────┘

Problem: Auth Service needs to validate tokens but doesn't 
have access to token store. How should I restructure this?
```

#### Text + Dateistruktur:

```markdown
My project structure is:

project/
├── src/
│   ├── api/
│   │   ├── __init__.py
│   │   ├── routes.py        ← Where should auth go?
│   │   └── middleware.py
│   ├── services/
│   │   ├── __init__.py
│   │   └── user_service.py
│   ├── models/
│   │   ├── __init__.py
│   │   └── user.py
│   └── utils/
│       ├── __init__.py
│       └── validators.py
└── tests/
    └── ...

Where should I place:
1. JWT token generation/validation logic?
2. Password hashing utilities?
3. Authentication middleware?

Please suggest best practices for this structure.
```

---

## 4. Entwicklungsprozess

### 4.1 Die Iterative Pyramide ⭐⭐⭐⭐⭐

```
                    ▲
                   ╱ ╲
                  ╱   ╲ Full Feature
                 ╱     ╲
                ╱───────╲
               ╱         ╲ Integration
              ╱───────────╲
             ╱             ╲ Business Logic
            ╱───────────────╲
           ╱                 ╲ Core Functions
          ╱─────────────────── ╲
         ╱                      ╲ Data Models
        ╱─────────────────────────╲
```

**Von unten nach oben bauen:**

#### Schritt 1: Datenmodelle

```markdown
Create the User model with these fields:
- id: UUID (primary key)
- email: string (unique, indexed, max 255)
- password_hash: string (max 255)
- name: string (max 100)
- is_active: boolean (default true)
- created_at: datetime (auto)
- updated_at: datetime (auto)

Include:
- SQLAlchemy ORM definition
- Pydantic schema for validation
- Type hints
- Table indexes
```

#### Schritt 2: Core Functions

```markdown
Based on the User model we just created [paste model],
now create these core utility functions:

1. hash_password(password: str) -> str
2. verify_password(password: str, hash: str) -> bool
3. generate_token(user_id: UUID) -> str
4. verify_token(token: str) -> Optional[UUID]

Requirements:
- Use bcrypt for hashing
- Use JWT for tokens (24h expiry)
- Include comprehensive error handling
- Add docstrings
- Include usage examples
```

#### Schritt 3: Business Logic

```markdown
Using the User model and utility functions we created,
implement the UserService class with these methods:

1. register(email, password, name) -> User
2. authenticate(email, password) -> Optional[str]  # Returns token
3. get_user_by_token(token) -> Optional[User]

Include:
- Input validation (email format, password strength)
- Duplicate email handling
- Rate limiting consideration
- Error logging
- Transaction management
```

#### Schritt 4: Integration (API Layer)

```markdown
Create FastAPI routes using the UserService we built:

POST /api/v1/auth/register
POST /api/v1/auth/login  
GET /api/v1/auth/me (requires authentication)

Include:
- Request/Response models (Pydantic)
- Dependency injection for UserService
- Error handling middleware
- OpenAPI documentation
- CORS configuration
```

#### Schritt 5: Full Feature (End-to-End)

```markdown
Now let's add the complete password reset flow:

1. Request reset: POST /api/v1/auth/reset-request
2. Verify token: GET /api/v1/auth/reset-verify/{token}
3. Set new password: POST /api/v1/auth/reset-confirm

This builds on our existing User model, utilities, and service.
[Paste relevant existing code]

Include email sending logic (mock for now) and token expiry (1 hour).
```

### 4.2 Das Request-Review-Refine Pattern

**Für jede Code-Komponente:**

#### 1️⃣ Request (Initial Implementation)

```markdown
Implement the hash_password function:
- Input: plain text password (string)
- Output: bcrypt hash (string)
- Use bcrypt work factor of 12
- Handle errors (empty password, bcrypt failure)
```

#### 2️⃣ Review (Critical Analysis)

```markdown
Review this hash_password implementation:
[paste code]

Check for:
1. Is the work factor appropriate for our security needs?
2. Are errors handled comprehensively?
3. Does it follow bcrypt best practices?
4. Are there any edge cases not covered?
5. Is the function thread-safe?
6. Should we add any logging?
```

#### 3️⃣ Refine (Improve Based on Feedback)

```markdown
Based on your review, you mentioned [issue].
Please provide an improved version that addresses:
- [Issue 1]
- [Issue 2]

Also add:
- Type hints for better IDE support
- Docstring with examples
- A simple unit test
```

### 4.3 Code Request Template

**Für optimale Ergebnisse, verwende dieses Template:**

```markdown
## Function/Class Request

**Name:** [function_name or ClassName]
**Purpose:** [What it does in one sentence]

**Signature:**
def function_name(param1: Type1, param2: Type2) -> ReturnType:
    """[Brief description]"""
    pass

**Inputs:**
- param1: [description, constraints, examples]
- param2: [description, constraints, examples]

**Output:**
- [Description of return value]
- [Possible return states]

**Business Logic:**
1. [Step 1]
2. [Step 2]
3. [Step 3]

**Edge Cases to Handle:**
- [Case 1: empty input]
- [Case 2: invalid format]
- [Case 3: database error]

**Error Handling:**
- Raise [ExceptionType] when [condition]
- Return [value] when [condition]

**Performance Considerations:**
- Expected call frequency: [e.g., 100/sec]
- Maximum processing time: [e.g., 50ms]
- Memory constraints: [if any]

**Dependencies:**
- [External library or function]
- [Database access]

**Testing Requirements:**
- Test with [scenario 1]
- Test with [scenario 2]
- Mock [dependency]

**Please Include:**
- [x] Complete implementation
- [x] Comprehensive error handling
- [x] Type hints
- [x] Docstring
- [x] Usage example
- [x] 3 unit test cases
```

---

## 5. Code-Qualität & Review

### 5.1 Die Code-Quality Checkliste ⭐⭐⭐⭐⭐

**Vor Akzeptanz von KI-generiertem Code:**

#### ✅ Funktionalität

- [ ] Code kompiliert/läuft ohne Fehler
- [ ] Erfüllt alle angegebenen Anforderungen
- [ ] Edge Cases sind abgedeckt
- [ ] Error Handling ist vollständig
- [ ] Input-Validierung ist implementiert

#### ✅ Lesbarkeit

- [ ] Klare, beschreibende Namen (Variablen, Funktionen, Klassen)
- [ ] Angemessene Code-Kommentare (warum, nicht was)
- [ ] Konsistente Formatierung
- [ ] Keine "magischen" Zahlen oder Strings
- [ ] Funktionen sind fokussiert (Single Responsibility)

#### ✅ Wartbarkeit

- [ ] Code ist modular aufgebaut
- [ ] Abhängigkeiten sind klar
- [ ] Keine Code-Duplikation (DRY)
- [ ] Einfach zu erweitern
- [ ] Konfiguration ist externalisiert

#### ✅ Performance

- [ ] Angemessene Algorithmen-Komplexität (Big-O)
- [ ] Keine offensichtlichen Bottlenecks
- [ ] Effiziente Datenstrukturen verwendet
- [ ] Ressourcen werden freigegeben
- [ ] Caching wo sinnvoll

#### ✅ Security

- [ ] Input wird validiert und sanitized
- [ ] Keine SQL-Injection-Möglichkeiten
- [ ] Keine XSS-Schwachstellen
- [ ] Sensible Daten sind geschützt
- [ ] Authentifizierung/Autorisierung korrekt
- [ ] Keine Secrets im Code

#### ✅ Testing

- [ ] Unit Tests sind vorhanden
- [ ] Test Coverage ist ausreichend
- [ ] Tests sind aussagekräftig
- [ ] Mocks/Stubs korrekt verwendet
- [ ] Integration Tests wo nötig

### 5.2 Code Review Prompts

#### Basic Review:

```markdown
Please review this code for quality and best practices:

[Your code here]

Analyze:
1. **Code Quality:** Style, naming, structure
2. **Potential Bugs:** Logic errors, edge cases
3. **Performance:** Inefficiencies, optimization opportunities
4. **Security:** Vulnerabilities, unsafe operations
5. **Maintainability:** Readability, documentation
6. **Best Practices:** Language-specific conventions

For each issue found:
- Severity: Critical / High / Medium / Low
- Description: What's wrong
- Recommendation: How to fix
- Example: Show improved code
```

#### Security-Focused Review:

```markdown
Perform a security audit on this code:

[Your code here]

Check for OWASP Top 10:
1. Injection flaws (SQL, NoSQL, Command, LDAP)
2. Broken authentication
3. Sensitive data exposure
4. XML External Entities (XXE)
5. Broken access control
6. Security misconfiguration
7. Cross-Site Scripting (XSS)
8. Insecure deserialization
9. Using components with known vulnerabilities
10. Insufficient logging & monitoring

For each vulnerability:
- Explain the risk
- Show how it could be exploited
- Provide secure alternative
- Reference OWASP guidelines
```

#### Performance Review:

```markdown
Analyze this code for performance optimization:

[Your code here]

Context:
- Runs [frequency, e.g., "1000 times per second"]
- Processes [data size, e.g., "arrays of 10,000 items"]
- Current performance: [metrics if available]

Analyze:
1. Time complexity (Big-O notation)
2. Space complexity
3. Bottlenecks (loops, I/O, database queries)
4. Optimization opportunities (caching, indexing, algorithms)
5. Trade-offs (readability vs. performance)

For each suggestion:
- Expected performance gain
- Implementation difficulty
- Potential side effects
- Code example
```

### 5.3 Refactoring mit KI

```markdown
Help me refactor this code to improve [maintainability/performance/readability]:

**Current Code:**
[Paste code that needs refactoring]

**Issues:**
- [Issue 1: e.g., "Too many nested loops"]
- [Issue 2: e.g., "Unclear variable names"]
- [Issue 3: e.g., "Code duplication in 3 places"]

**Goals:**
- [Goal 1: e.g., "Extract reusable functions"]
- [Goal 2: e.g., "Improve naming"]
- [Goal 3: e.g., "Reduce cyclomatic complexity"]

**Constraints:**
- Must maintain backward compatibility
- Cannot change public API
- Performance must not degrade

**Please provide:**
1. Step-by-step refactoring plan
2. Refactored code with explanations
3. Before/after comparison
4. Any potential risks or side effects
5. Test cases to verify refactoring correctness
```

---

## 6. Testing & Debugging

### 6.1 Test-First Approach ⭐⭐⭐⭐⭐

**Generiere Tests BEVOR oder ZUSAMMEN mit Code:**

```markdown
I need to implement a function that validates email addresses.

Before implementing, let's define the test cases:

**Test Cases Required:**

1. **Happy Path:**
   - Input: "user@example.com" → Should return True
   - Input: "test.user@domain.co.uk" → Should return True

2. **Edge Cases:**
   - Input: "a@b.c" → Should return True (minimum valid)
   - Input: "user+tag@example.com" → Should return True (plus addressing)
   - Input: "user@subdomain.example.com" → Should return True (subdomain)

3. **Invalid Cases:**
   - Input: "" → Should return False (empty)
   - Input: "notanemail" → Should return False (no @)
   - Input: "@example.com" → Should return False (no local part)
   - Input: "user@" → Should return False (no domain)
   - Input: "user @example.com" → Should return False (whitespace)
   - Input: "user@.com" → Should return False (no domain name)

4. **Security Cases:**
   - Input: "user@example.com<script>" → Should return False (XSS attempt)
   - Input: "'; DROP TABLE users--@example.com" → Should return False (SQL injection)

5. **Type Safety:**
   - Input: None → Should raise TypeError
   - Input: 123 → Should raise TypeError
   - Input: ["user@example.com"] → Should raise TypeError

Please provide:
1. pytest test suite covering all cases above
2. Then the actual validate_email() implementation
3. Explanation of regex pattern or validation library used
```

### 6.2 Debugging-Template

```markdown
## Debug Request

**Problem Statement:**
[Brief description of the issue]

**Expected Behavior:**
[What should happen - be specific]

**Actual Behavior:**
[What actually happens - include error messages]

**Error Details:**
# Full error message
[Paste complete error]

# Stack trace
[Paste complete stack trace]

**Relevant Code:**
# Function where error occurs
[Paste function code]

# Calling code
[Paste how the function is called]

# Related components
[Paste any related code that might be involved]

**Environment:**
- OS: [e.g., Ubuntu 22.04]
- Language Version: [e.g., Python 3.11.5]
- Framework Version: [e.g., FastAPI 0.104.1]
- Dependencies: [relevant libraries and versions]

**Data Context:**
# Input that causes the error
input_data = [paste actual input]

# Database state (if relevant)
# Sample data in relevant tables

**What I've Tried:**
1. [Attempt 1] → Result: [what happened]
2. [Attempt 2] → Result: [what happened]
3. [Attempt 3] → Result: [what happened]

**What I've Verified:**
- [x] Database connection is working
- [x] Input data is in correct format
- [x] All dependencies are installed
- [ ] Similar code works elsewhere

**My Hypothesis:**
[Your theory about what's causing the issue and why]

**Debug Strategy Needed:**
1. Help me identify the root cause
2. Suggest systematic debugging steps
3. Provide potential fixes with explanations
4. Recommend how to prevent this in future
```

### 6.3 Test Generation Prompts

#### Unit Tests:

```markdown
Generate comprehensive unit tests for this function:

[Paste your function]

**Test Framework:** [pytest/unittest/Jest/JUnit]

**Coverage Required:**
1. Happy path scenarios (2-3 tests)
2. Edge cases (3-4 tests)
3. Error conditions (3-4 tests)
4. Boundary values (2-3 tests)
5. Type validation (if applicable)

**For each test include:**
- Descriptive test name
- Arrange-Act-Assert structure
- Clear assertion messages
- Test data explanation

**Additional Requirements:**
- Use fixtures for setup/teardown
- Mock external dependencies (database, API calls)
- Parametrize where appropriate
- Include test docstrings

**Example test structure:**
def test_feature_name_with_valid_input():
    """Test that function handles valid input correctly."""
    # Arrange
    input_data = ...
    expected = ...
    
    # Act
    result = function(input_data)
    
    # Assert
    assert result == expected, "Should return expected value for valid input"
```

#### Integration Tests:

```markdown
Create integration tests for this API endpoint:

**Endpoint:** POST /api/v1/users

**Components Involved:**
- API Route: [paste route code]
- Service Layer: [paste service code]
- Database Model: [paste model code]

**Test Scenarios:**
1. **Successful user creation**
   - Valid input
   - Returns 201
   - User exists in database

2. **Duplicate email handling**
   - Email already exists
   - Returns 409 Conflict
   - Database unchanged

3. **Invalid input validation**
   - Missing required fields
   - Invalid email format
   - Password too weak
   - Returns 400

4. **Database failure handling**
   - Simulate DB connection error
   - Returns 500
   - Proper error logging

**Include:**
- Test database setup/teardown
- Test fixtures
- API client mock
- Database transaction rollback
- Request/response validation
```

### 6.4 Fehler-Analyse

```markdown
Analyze this error and provide debugging guidance:

**Error:**
[Paste complete error message]

**Stack Trace:**
[Paste complete stack trace]

**Code Context:**
[Paste relevant code sections]

**Please provide:**

1. **Root Cause Analysis:**
   - What is causing this error?
   - Why is it happening?
   - Which line is the actual problem?

2. **Debugging Strategy:**
   - Step 1: [e.g., "Add logging before line 45"]
   - Step 2: [e.g., "Check variable state at breakpoint"]
   - Step 3: [e.g., "Verify database connection"]

3. **Potential Fixes:**
   - Quick fix: [immediate solution]
   - Proper fix: [correct long-term solution]
   - Alternative approach: [different way to achieve goal]

4. **Prevention:**
   - How to prevent this error in future?
   - What validation should be added?
   - What tests should cover this?

5. **Related Issues:**
   - Are there similar problems elsewhere?
   - What other code might be affected?
```

---

## 7. Security & Performance

### 7.1 Security Audit Template ⭐⭐⭐⭐⭐

```markdown
Perform a comprehensive security audit on this code:

[Paste your code]

**Context:**
- Application Type: [Web API / CLI / Service]
- Exposure: [Public / Internal / Private]
- Data Sensitivity: [PII / Financial / Public / Internal]
- Compliance Requirements: [GDPR / HIPAA / PCI-DSS / None]

**OWASP Top 10 Analysis:**

1. **Injection:**
   - Check for SQL/NoSQL injection
   - Command injection
   - LDAP injection
   - Check input sanitization

2. **Broken Authentication:**
   - Password storage method
   - Session management
   - Token security
   - Multi-factor authentication

3. **Sensitive Data Exposure:**
   - Data at rest encryption
   - Data in transit encryption
   - Logging of sensitive data
   - Error message information leakage

4. **XML External Entities (XXE):**
   - XML parser configuration
   - External entity processing

5. **Broken Access Control:**
   - Authorization checks
   - Insecure direct object references
   - Missing function level access control

6. **Security Misconfiguration:**
   - Default credentials
   - Unnecessary features enabled
   - Security headers
   - Error handling configuration

7. **Cross-Site Scripting (XSS):**
   - Input validation
   - Output encoding
   - Content Security Policy

8. **Insecure Deserialization:**
   - Pickle/eval usage
   - Object deserialization
   - Type validation

9. **Using Components with Known Vulnerabilities:**
   - Dependency versions
   - Known CVEs
   - Update frequency

10. **Insufficient Logging & Monitoring:**
    - Security event logging
    - Error tracking
    - Audit trail
    - Alerting

**For each issue found, provide:**
- Severity: Critical / High / Medium / Low
- Vulnerability type
- Attack scenario
- Proof of concept (if safe)
- Remediation code
- Prevention strategy
- References (CWE, CVE, OWASP)
```

### 7.2 Performance Optimization

```markdown
Optimize this code for performance:

[Paste code to optimize]

**Current Performance:**
- Execution time: [e.g., 2.5 seconds]
- Memory usage: [e.g., 500 MB]
- Request rate: [e.g., 10 req/sec]

**Performance Requirements:**
- Target execution time: [e.g., < 200ms]
- Max memory usage: [e.g., < 100 MB]
- Target request rate: [e.g., 100 req/sec]

**Context:**
- Input size: [e.g., "arrays of 10,000 items"]
- Call frequency: [e.g., "1000 times per second"]
- Hardware: [e.g., "4 CPU cores, 8GB RAM"]

**Analysis Required:**

1. **Complexity Analysis:**
   - Current time complexity (Big-O)
   - Current space complexity
   - Bottleneck identification

2. **Optimization Opportunities:**
   - Algorithm improvements
   - Data structure changes
   - Caching strategies
   - Database query optimization
   - Parallelization potential

3. **Trade-offs:**
   - Performance vs. readability
   - Time vs. space
   - Complexity vs. maintainability

4. **Implementation:**
   - Provide optimized code
   - Show before/after comparison
   - Explain each optimization
   - Estimate performance gain

5. **Verification:**
   - Benchmark approach
   - Profiling recommendations
   - Test cases to validate
```

### 7.3 Security-Specific Prompts

#### Input Validation:

```markdown
Review this input validation for security:

[Paste validation code]

**Check for:**
- Whitelist vs. blacklist approach
- Length limits
- Character restrictions
- Format validation (email, phone, etc.)
- Type checking
- Encoding validation
- Injection prevention

**Provide:**
- Security assessment
- Attack scenarios
- Improved validation code
- Regex patterns if needed
- Test cases including malicious inputs
```

#### Authentication Review:

```markdown
Review this authentication implementation:

[Paste auth code]

**Verify:**
- Password hashing (algorithm, salt, work factor)
- Token generation (randomness, expiration)
- Session management (storage, invalidation)
- Brute force protection (rate limiting, lockout)
- Secure password reset flow
- Remember-me functionality
- Logout implementation

**Check against:**
- OWASP Authentication Cheat Sheet
- NIST Password Guidelines
- Industry best practices

**Provide secure alternatives for any issues found.**
```

---

## 8. Wartung & Dokumentation

### 8.1 Code-Dokumentation generieren

```markdown
Generate comprehensive documentation for this code:

[Paste your code]

**Documentation Required:**

1. **Module/File-Level:**
   - Purpose and scope
   - Dependencies
   - Usage examples
   - Design decisions

2. **Class-Level:**
   - Class purpose
   - Attributes description
   - Usage examples
   - Relationship to other classes

3. **Function-Level:**
   - Docstring (Google/NumPy/Sphinx style)
   - Parameters with types and descriptions
   - Return value with type and description
   - Raises (exceptions)
   - Examples
   - Time/space complexity (if relevant)

4. **Inline Comments:**
   - Complex logic explanation
   - Non-obvious decisions
   - Workarounds and technical debt
   - TODOs for future improvements

**Format:** [Google Style / NumPy Style / reStructuredText]

**Also include:**
- Type hints for all functions
- Meaningful variable names
- Constants explanation
```

### 8.2 README Generator

```markdown
Create a comprehensive README.md for this project:

**Project Name:** [Name]
**Description:** [Brief description]

**Project Structure:**
[Paste project tree]

**Key Features:**
- [Feature 1]
- [Feature 2]
- [Feature 3]

**Tech Stack:**
- [Technology 1]
- [Technology 2]

**README Should Include:**

1. **Project Title & Description**
   - Clear, concise description
   - Key features highlight
   - Use case scenarios

2. **Badges** (if applicable)
   - Build status
   - Test coverage
   - Version
   - License

3. **Installation**
   - Prerequisites
   - Step-by-step installation
   - Dependency installation
   - Environment setup

4. **Quick Start**
   - Minimal working example
   - Common use cases
   - Configuration basics

5. **Usage**
   - Detailed examples
   - API documentation (if applicable)
   - Command-line usage
   - Configuration options

6. **Architecture** (optional)
   - System overview
   - Component description
   - Data flow

7. **Development**
   - Setting up dev environment
   - Running tests
   - Code style guidelines
   - Contributing guidelines

8. **Troubleshooting**
   - Common issues and solutions
   - FAQ

9. **License**
   - License type
   - Copyright information

10. **Contact/Support**
    - Maintainer information
    - How to get help
    - Issue reporting

Use proper Markdown formatting with:
- Clear headings
- Code blocks with syntax highlighting
- Links to relevant resources
- Tables for structured data
```

### 8.3 API-Dokumentation

```markdown
Generate API documentation for these endpoints:

[Paste API route code]

**For each endpoint include:**

**1. Overview:**
- Method and path
- Brief description
- Authentication required (yes/no)

**2. Request:**
- Headers
- Query parameters (with types, required/optional)
- Request body (with JSON schema)
- Example request

**3. Response:**
- Success response (status code, body)
- Error responses (all possible status codes)
- Response body schema
- Example responses

**4. Error Codes:**
- All possible error codes
- Error descriptions
- Error response format

**5. Examples:**
- cURL example
- Python requests example
- JavaScript fetch example

**6. Notes:**
- Rate limiting
- Pagination (if applicable)
- Deprecation warnings
- Related endpoints

**Format:** [OpenAPI/Swagger / Markdown / ReDoc]
```

### 8.4 Changelog Generator

```markdown
Generate a CHANGELOG.md entry based on these changes:

**Version:** [e.g., 2.1.0]
**Release Date:** [e.g., 2024-11-19]

**Changes Made:**
[Paste git diff or list of changes]

**Follow [Keep a Changelog](https://keepachangelog.com/) format:**

### [Version] - Date

#### Added
- New features
- New functionality

#### Changed
- Changes to existing functionality
- Updated dependencies

#### Deprecated
- Soon-to-be removed features
- Migration guide

#### Removed
- Removed features
- Backwards incompatible changes

#### Fixed
- Bug fixes
- Security fixes

#### Security
- Security improvements
- Vulnerability patches

**Also include:**
- Breaking changes (highlighted)
- Migration guide (if breaking changes)
- Contributors (if applicable)
- Link to full diff
```

---

## 9. Anti-Patterns & Fallstricke

### 9.1 Häufige Fehler vermeiden ⭐⭐⭐⭐⭐

#### ❌ NIEMALS tun:

**1. Blindes Copy-Paste**

```markdown
❌ DON'T:
Copy GPT code directly into production without understanding

✅ DO:
1. Read and understand every line
2. Verify logic is correct
3. Check for security issues
4. Test thoroughly
5. Review with team if critical
```

**2. Vage Anfragen**

```markdown
❌ DON'T: "Fix this bug"
❌ DON'T: "Make it faster"
❌ DON'T: "Add authentication"

✅ DO: Use specific, detailed requests (see Section 3)
```

**3. Fehlende Kontext-Updates**

```markdown
❌ DON'T:
Message 1: "Create User class"
Message 10: "Update the login method" (GPT has forgotten the User class)

✅ DO:
Message 10: "Here's the current User class [paste code]. 
Update the login method to..."
```

**4. Ignorieren von Security-Warnungen**

```markdown
❌ DON'T:
Ignore GPT's security warnings
Skip validation "for now"
Store passwords in plain text "temporarily"

✅ DO:
Take security seriously from day one
Implement all suggested security measures
Review code for vulnerabilities
```

**5. Über-Optimierung**

```markdown
❌ DON'T:
Ask for micro-optimizations before code works
Sacrifice readability for minor performance gains
Optimize without profiling

✅ DO:
Make it work first
Make it right second
Make it fast last (and only if needed)
```

**6. Fehlende Tests**

```markdown
❌ DON'T:
Skip tests because "GPT wrote the code"
Trust code without verification
Deploy without testing

✅ DO:
Write tests for all critical code
Test edge cases and error conditions
Verify behavior matches requirements
```

### 9.2 KI-Halluzinationen erkennen

**GPT kann halluzinieren bei:**

#### 1. Library-Funktionen

```python
# GPT könnte vorschlagen:
df.remove_duplicates()  # ❌ Existiert nicht in pandas

# Tatsächlich:
df.drop_duplicates()    # ✅ Korrekt
```

**Lösung:**

```markdown
When suggesting pandas code, please verify function names 
against the official pandas documentation. If you're unsure, 
say so explicitly.
```

#### 2. API-Signaturen

```python
# GPT könnte sagen:
requests.get(url, timeout=30, verify_ssl=True)  # ❌ Falscher Parameter

# Tatsächlich:
requests.get(url, timeout=30, verify=True)      # ✅ Korrekt
```

**Lösung:**

```markdown
Double-check this code against the official [library] documentation.
Are these the correct parameter names and types?
```

#### 3. Version-spezifische Features

```python
# GPT könnte sagen (für Python 3.8):
data: dict[str, int] = {}  # ❌ Erfordert Python 3.9+

# Für Python 3.8:
from typing import Dict
data: Dict[str, int] = {}  # ✅ Korrekt
```

**Lösung:**

```markdown
We're using Python 3.8. Please ensure all syntax and features 
are compatible with this version. If you suggest newer features, 
explicitly mention the minimum version required.
```

### 9.3 Verifikations-Checkliste

**Vor Verwendung von KI-generiertem Code:**

```markdown
## Code Verification Checklist

### 1. Syntax & Compilation
- [ ] Code runs without syntax errors
- [ ] All imports are available
- [ ] Type hints are correct

### 2. Logic Verification
- [ ] Algorithm logic is sound
- [ ] Edge cases are handled
- [ ] Error conditions are caught
- [ ] Return values are correct

### 3. API/Library Verification
- [ ] Function/method names exist in library
- [ ] Parameters are correct
- [ ] Versions are compatible
- [ ] No deprecated features used

### 4. Security Check
- [ ] Input is validated
- [ ] No injection vulnerabilities
- [ ] Sensitive data is protected
- [ ] Authentication is proper

### 5. Performance Check
- [ ] No obvious bottlenecks
- [ ] Complexity is acceptable
- [ ] Memory usage is reasonable
- [ ] Database queries are optimized

### 6. Testing
- [ ] Unit tests pass
- [ ] Integration tests pass
- [ ] Edge cases tested
- [ ] Error handling tested

### 7. Documentation
- [ ] Code is commented
- [ ] Docstrings are present
- [ ] README is updated
- [ ] API docs are accurate

Only deploy when ALL items are checked ✓
```

### 9.4 Red Flags - Sofort überprüfen

**Diese Code-Muster erfordern besondere Aufmerksamkeit:**

```python
# 🚩 Red Flag 1: String Concatenation in SQL
query = "SELECT * FROM users WHERE id = " + user_id  # ❌ SQL Injection!

# ✅ Correct:
query = "SELECT * FROM users WHERE id = ?"
cursor.execute(query, (user_id,))

# 🚩 Red Flag 2: eval() oder exec()
eval(user_input)  # ❌ Code Injection!

# ✅ Correct: Use safe parsing (ast.literal_eval or json.loads)

# 🚩 Red Flag 3: Unvalidated User Input
password = request.form['password']
# Store directly without validation  # ❌ Security Risk!

# ✅ Correct: Validate, sanitize, hash

# 🚩 Red Flag 4: Hardcoded Secrets
API_KEY = "sk_live_1234567890abcdef"  # ❌ Security Risk!

# ✅ Correct: Use environment variables

# 🚩 Red Flag 5: Overly Generic Exceptions
try:
    ...
except Exception:  # ❌ Catches too much!
    pass

# ✅ Correct: Catch specific exceptions

# 🚩 Red Flag 6: Missing Resource Cleanup
file = open('data.txt')
# No close() or context manager  # ❌ Resource Leak!

# ✅ Correct: Use context manager

# 🚩 Red Flag 7: Inefficient Loops
for user in users:
    for post in posts:
        if post.user_id == user.id:  # ❌ O(n²)!
            ...

# ✅ Correct: Use hash map or join

# 🚩 Red Flag 8: Mutable Default Arguments
def add_item(item, items=[]):  # ❌ Shared state!
    items.append(item)
    return items

# ✅ Correct: Use None and create new list
```

**Prompt für Red-Flag-Check:**

```markdown
Review this code for common anti-patterns and red flags:

[Paste code]

Specifically check for:
1. SQL injection vulnerabilities
2. Use of eval/exec
3. Unvalidated user input
4. Hardcoded secrets
5. Overly generic exception handling
6. Resource leaks (unclosed files/connections)
7. Inefficient algorithms (nested loops, etc.)
8. Mutable default arguments
9. Race conditions
10. Memory leaks

Flag any suspicious patterns and provide secure alternatives.
```

---

## 10. Workflow-Templates

### 10.1 Complete Feature Implementation

```markdown
# Complete Feature Workflow

## Phase 1: Requirements & Planning

### 1.1 Define Requirements
**Feature:** [Feature name]
**User Story:** As a [user], I want to [action] so that [benefit]

**Functional Requirements:**
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

**Non-Functional Requirements:**
- Performance: [e.g., < 200ms response time]
- Security: [e.g., OWASP compliant]
- Scalability: [e.g., handle 1000 concurrent users]

### 1.2 Design API/Interface
[Define endpoints, signatures, data models]

### 1.3 Plan Implementation
[Break into small, manageable tasks]

---

## Phase 2: Implementation

### 2.1 Create Data Models
Prompt:
Create [models] with these specifications:
[Detailed specs]

### 2.2 Implement Business Logic
Prompt:
Implement [service/controller] with these methods:
[Detailed specs]

### 2.3 Create API Layer
Prompt:
Create API endpoints:
[Endpoint specs]

### 2.4 Add Error Handling
Prompt:
Review and add comprehensive error handling:
[Current code]

---

## Phase 3: Testing

### 3.1 Generate Unit Tests
Prompt:
Create unit tests for:
[Component to test]
Coverage requirements: [specs]

### 3.2 Generate Integration Tests
Prompt:
Create integration tests for:
[Feature workflow]

### 3.3 Security Testing
Prompt:
Perform security audit on:
[Code to audit]

---

## Phase 4: Documentation

### 4.1 Code Documentation
Prompt:
Add comprehensive documentation to:
[Code]

### 4.2 API Documentation
Prompt:
Generate API docs for:
[Endpoints]

### 4.3 User Documentation
Prompt:
Create user guide for:
[Feature]

---

## Phase 5: Review & Refinement

### 5.1 Code Review
Prompt:
Review this code for quality:
[Complete feature code]

### 5.2 Performance Review
Prompt:
Analyze performance of:
[Critical paths]

### 5.3 Security Review
Prompt:
Final security audit:
[All feature code]

---

## Phase 6: Deployment Preparation

### 6.1 Version Control
- [ ] All code committed
- [ ] Descriptive commit messages
- [ ] Branch merged
- [ ] Tagged release

### 6.2 Documentation
- [ ] README updated
- [ ] CHANGELOG updated
- [ ] API docs published
- [ ] Migration guide (if needed)

### 6.3 Deployment Checklist
- [ ] All tests passing
- [ ] Security audit complete
- [ ] Performance acceptable
- [ ] Monitoring configured
- [ ] Rollback plan ready
```

### 10.2 Quick Bug Fix Workflow

```markdown
# Bug Fix Workflow

## Step 1: Document Bug
**Bug ID:** [ID]
**Severity:** [Critical/High/Medium/Low]
**Affected Component:** [Component]

**Description:**
[What's broken]

**Steps to Reproduce:**
1. [Step 1]
2. [Step 2]
3. [Step 3]

**Expected vs Actual:**
- Expected: [behavior]
- Actual: [behavior]

---

## Step 2: Gather Context
Prompt:
Help me debug this issue:

Error: [error message]
Stack Trace: [trace]
Relevant Code: [code]
Context: [additional info]

Please analyze the root cause.

---

## Step 3: Implement Fix
Prompt:
Based on your analysis, provide a fix for:
[Issue]

Requirements:
- Minimal code changes
- No breaking changes
- Include tests
- Explain the fix

---

## Step 4: Verify Fix
- [ ] Bug is resolved
- [ ] No regressions introduced
- [ ] Tests added/updated
- [ ] Code reviewed

---

## Step 5: Document
- [ ] Commit message explains fix
- [ ] Issue tracker updated
- [ ] CHANGELOG updated
- [ ] Knowledge base updated (if pattern)
```

### 10.3 Code Refactoring Workflow

```markdown
# Refactoring Workflow

## Step 1: Identify Need
**Reason for Refactoring:**
- [ ] Code smells detected
- [ ] Performance issues
- [ ] Difficult to maintain
- [ ] Adding new features difficult
- [ ] Technical debt accumulation

**Target Code:**
[Paste code to refactor]

**Problems:**
- [Problem 1]
- [Problem 2]
- [Problem 3]

---

## Step 2: Plan Refactoring
Prompt:
Analyze this code and create refactoring plan:
[Code]

Issues: [list issues]
Goals: [list goals]
Constraints: [list constraints]

Please provide:
1. Step-by-step refactoring plan
2. Risk assessment
3. Testing strategy

---

## Step 3: Create Safety Net
- [ ] All existing tests passing
- [ ] Code coverage measured
- [ ] Additional tests for edge cases
- [ ] Git checkpoint created

---

## Step 4: Refactor Incrementally
For each refactoring step:

Prompt:
Refactor [specific aspect]:
Current code: [paste]
Goal: [specific goal]
Please provide refactored version with explanation.

After each step:
- [ ] Tests still pass
- [ ] Functionality unchanged
- [ ] Code reviewed
- [ ] Committed

---

## Step 5: Verify Improvements
- [ ] All tests pass
- [ ] Performance measured (if relevant)
- [ ] Code complexity reduced
- [ ] Maintainability improved
- [ ] Team approval

---

## Step 6: Document
- [ ] Refactoring documented
- [ ] Architecture docs updated
- [ ] Team informed
- [ ] Knowledge shared
```

---

## 📋 Quick Reference Cards

### Card 1: Perfect Prompt Formula

```
[ROLE] You are an expert [LANGUAGE/DOMAIN] developer

[CONTEXT]
- Tech Stack: [specific versions]
- Architecture: [pattern]
- Constraints: [specific requirements]

[TASK]
Implement [specific feature] with:
- [Requirement 1]
- [Requirement 2]
- [Requirement 3]

[DELIVERABLES]
Provide:
1. Complete implementation
2. Error handling
3. Security considerations
4. Test cases
5. Documentation

[QUALITY CRITERIA]
- No placeholders
- Production-ready
- Best practices followed
- Performant
- Secure
```

### Card 2: Code Review Prompt

```
Review this code:

[code]

Analyze:
1. Quality & best practices
2. Potential bugs
3. Performance
4. Security
5. Maintainability

For each issue:
- Severity
- Description
- Fix
- Example
```

### Card 3: Debugging Prompt

```
Debug this issue:

Problem: [description]
Expected: [behavior]
Actual: [behavior]

Error: [message]
Trace: [stack trace]
Code: [relevant code]

Context:
- [Key info 1]
- [Key info 2]

Tried:
- [Attempt 1]
- [Attempt 2]

Please provide:
1. Root cause
2. Debug steps
3. Fix
4. Prevention
```

### Card 4: Test Generation

```
Generate tests for:

[code]

Coverage:
1. Happy path (2-3 tests)
2. Edge cases (3-4 tests)
3. Errors (3-4 tests)
4. Boundaries (2-3 tests)

Framework: [name]
Include:
- Fixtures
- Mocks
- Assertions
- Docstrings
```

---

## 🎯 Abschließende Best Practices

### Die 10 Gebote des KI-Coding

1. **Du sollst Kontext geben** - Umfassend und präzise
2. **Du sollst verstehen** - Jeden Code, bevor du ihn nutzt
3. **Du sollst iterieren** - Kleine Schritte, große Erfolge
4. **Du sollst testen** - Immer und ausführlich
5. **Du sollst sichern** - Git ist dein Freund
6. **Du sollst reviewen** - Kritisch und gründlich
7. **Du sollst dokumentieren** - Für dein zukünftiges Ich
8. **Du sollst hinterfragen** - "Warum?" ist eine gute Frage
9. **Du sollst sichern (Security)** - Von Anfang an
10. **Du sollst lernen** - Aus jedem Code, den KI generiert

---

## 📚 Zusätzliche Ressourcen

### Empfohlene Lektüre:

- OWASP Top 10
- Clean Code (Robert C. Martin)
- Design Patterns (Gang of Four)
- Effective [Your Language] (sprachspezifisch)

### Tools zur Code-Qualität:

- SonarQube / SonarLint
- Black / Prettier (Formatierung)
- Pylint / ESLint (Linting)
- Bandit / Safety (Security Scanning)
- pytest-cov / Istanbul (Coverage)

### Online-Ressourcen:

- Official Documentation (immer die erste Anlaufstelle)
- Stack Overflow (für spezifische Probleme)
- GitHub (für Code-Beispiele)
- OWASP (für Security)

---

