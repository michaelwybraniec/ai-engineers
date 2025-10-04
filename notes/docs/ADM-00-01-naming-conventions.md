# Document Naming Conventions

**Document ID:** ADM-00-01  
**Document Version:** 1.0  
**Effective Date:** 2024-07-01  
**Review Date:** 2024-07-01  
**Approved By:** Core Team

---

## 1. Naming Convention Overview

### 1.1 Purpose
This document establishes the official naming conventions for all community documentation to ensure consistency, organization, and professional standards.

### 1.2 Scope
This convention applies to all documents in the community documentation system including policies, procedures, guidelines, and reference materials.

### 1.3 Authority
The core team has authority to modify these naming conventions in accordance with community needs and best practices.

---

## 2. File Naming Structure

### 2.1 Basic Format
**Format:** `XX-XX-descriptive-name.md`

**Components:**
- **Category Number:** `XX` (01-06 for main categories, 00 for quick references)
- **Document Number:** `XX` (01-99 within category)
- **Descriptive Name:** `descriptive-name` (kebab-case)
- **File Extension:** `.md` (Markdown)

### 2.2 Examples
- `01-01-community-vision.md`
- `02-03-mentorship-program.md`
- `04-02-scam-prevention.md`
- `06-04-website-technical.md`

---

## 3. Category System

### 3.1 Main Categories

#### 3.1.1 Quick References (00)
- **Prefix:** `REF`
- **Purpose:** Quick access guides and summaries
- **Examples:** Contact information, quick start guides, policy summaries

#### 3.1.2 Governance (01)
- **Prefix:** `GOV`
- **Purpose:** Core governance and leadership documents
- **Examples:** Community vision, governance model, core team roles

#### 3.1.3 Members (02)
- **Prefix:** `MEM`
- **Purpose:** Member management and engagement
- **Examples:** Member engagement, onboarding, mentorship programs

#### 3.1.4 Communication (03)
- **Prefix:** `COM`
- **Purpose:** Communication standards and content guidelines
- **Examples:** Communication guidelines, content guidelines, code of conduct

#### 3.1.5 Safety & Security (04)
- **Prefix:** `SAF`
- **Purpose:** Safety, security, and protection policies
- **Examples:** Ban policy, scam prevention, crisis management, privacy policy

#### 3.1.6 Operations (05)
- **Prefix:** `OPS`
- **Purpose:** Operational procedures and management
- **Examples:** Event management, financial management, partnerships, projects

#### 3.1.7 Technology (06)
- **Prefix:** `TEC`
- **Purpose:** Technical specifications and systems
- **Examples:** Website specifications, intellectual property, analytics

### 3.2 Administrative Categories

#### 3.2.1 Administrative (ADM)
- **Prefix:** `ADM`
- **Purpose:** Administrative, management, and process documents
- **Examples:** Change management, README, naming conventions

---

## 4. Document ID System

### 4.1 Document ID Format
**Format:** `PREFIX-XX-XX`

**Components:**
- **Prefix:** Category prefix (GOV, MEM, COM, SAF, OPS, TEC, REF, ADM)
- **Category Number:** `XX` (01-06)
- **Document Number:** `XX` (01-99)

### 4.2 Document ID Examples
- `GOV-01-01` (Community Vision)
- `MEM-02-03` (Mentorship Program)
- `SAF-04-02` (Scam Prevention)
- `TEC-06-04` (Website Technical)
- `ADM-00-01` (Naming Conventions)

---

## 5. Directory Structure

### 5.1 Main Directory Organization
```
docs/
├── 00-Quick References/     # Quick access documents
├── 01-Governance/          # Core governance documents
├── 02-Members/             # Member management
├── 03-Communication/       # Communication standards
├── 04-Safety-Security/     # Safety and security policies
├── 05-Operations/          # Operational procedures
├── 06-Technology/          # Technical specifications
├── Administrative/         # Admin and management docs
└── templates/              # Document templates
```

### 5.2 Directory Naming Rules
- **Use hyphens:** `01-Governance/` not `01_Governance/`
- **Use title case:** `Quick References/` not `quick references/`
- **Be descriptive:** `Safety-Security/` not `Security/`
- **Keep consistent:** All directories follow same pattern

---

## 6. Naming Rules and Guidelines

### 6.1 File Naming Rules

#### 6.1.1 Do's
- **Use kebab-case:** `member-engagement.md` not `member_engagement.md`
- **Be descriptive:** `scam-prevention.md` not `scam.md`
- **Keep it concise:** `ban-policy.md` not `community-ban-policy-and-discipline.md`
- **Use consistent numbering:** Sequential within categories
- **Include document ID:** Always include in document header

#### 6.1.2 Don'ts
- **Don't use spaces:** `ban policy.md` ❌
- **Don't use underscores:** `ban_policy.md` ❌
- **Don't use camelCase:** `banPolicy.md` ❌
- **Don't skip numbers:** 01, 02, 04 (missing 03) ❌
- **Don't duplicate numbers:** Two files with same number ❌

### 6.2 Descriptive Name Guidelines

#### 6.2.1 Naming Principles
- **Clear and Descriptive:** Name should clearly indicate content
- **Concise:** Keep names as short as possible while being clear
- **Consistent:** Use consistent terminology across similar documents
- **Professional:** Use professional, formal language

#### 6.2.2 Common Suffixes
- **Policy:** `ban-policy.md`, `privacy-policy.md`
- **Guidelines:** `communication-guidelines.md`, `content-guidelines.md`
- **Management:** `event-management.md`, `financial-management.md`
- **Program:** `mentorship-program.md`, `onboarding-program.md`

---

## 7. Version Control Integration

### 7.1 File Naming for Versions
- **Current Version:** `01-01-community-vision.md`
- **Draft Version:** `01-01-community-vision-draft.md`
- **Archived Version:** `01-01-community-vision-v1.0.md`

### 7.2 Document Header Standards
```markdown
# Document Title

**Document ID:** GOV-01-01
**Document Version:** 1.0
**Effective Date:** 2024-07-01
**Review Date:** 2024-07-01
**Approved By:** Core Team
```

---

## 8. Implementation Guidelines

### 8.1 For New Documents

#### 8.1.1 Process
1. **Determine Category:** Which category does it belong to?
2. **Assign Number:** Next available number in category
3. **Create Name:** Descriptive kebab-case name
4. **Add Document ID:** Follow PREFIX-XX-XX format
5. **Update Index:** Add to README and policy summary

#### 8.1.2 Checklist
- [ ] Category determined
- [ ] Number assigned (next available)
- [ ] Name created (descriptive, kebab-case)
- [ ] Document ID assigned
- [ ] File created with proper header
- [ ] Index updated

### 8.2 For Document Changes

#### 8.2.1 Process
1. **Keep Same ID:** Document ID never changes
2. **Update Version:** Increment version number
3. **Update Dates:** Effective and review dates
4. **Update Cross-References:** Update any links to document

#### 8.2.2 Checklist
- [ ] Document ID unchanged
- [ ] Version number incremented
- [ ] Dates updated
- [ ] Cross-references updated
- [ ] Change log updated

---

## 9. Quality Assurance

### 9.1 Naming Review Process

#### 9.1.1 Review Criteria
- **Consistency:** Follows established naming convention
- **Clarity:** Name clearly indicates document purpose
- **Uniqueness:** No duplicate names or numbers
- **Professionalism:** Uses professional, appropriate language

#### 9.1.2 Review Process
1. **Initial Review:** Check against naming convention
2. **Peer Review:** Another team member reviews
3. **Final Approval:** Core team approval
4. **Implementation:** Apply naming convention

### 9.2 Common Issues and Solutions

#### 9.2.1 Common Issues
- **Inconsistent naming:** Mix of kebab-case and other formats
- **Unclear names:** Names that don't clearly indicate purpose
- **Duplicate numbers:** Multiple documents with same number
- **Missing document IDs:** Documents without proper IDs

#### 9.2.2 Solutions
- **Standardization:** Apply consistent naming convention
- **Clarification:** Use more descriptive names
- **Renumbering:** Reassign numbers to avoid duplicates
- **ID Assignment:** Add proper document IDs

---

## 10. Contact Information

### 10.1 Naming Convention Support
- **Document Manager:** community@ai-engineers.org
- **Change Requests:** community@ai-engineers.org
- **General Inquiries:** community@ai-engineers.org

### 10.2 Related Documents
- **[Change Management](ADM-00-02-change-management.md)** - Document change process
- **[README](ADM-00-03-README.md)** - Documentation overview
- **[Document Template](templates/document-template.md)** - Standard template

---

**Document Owner:** Core Team  
**Next Review:** 2024-07-01  
**Distribution:** All Documentation Contributors
