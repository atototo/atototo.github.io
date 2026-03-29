# Portfolio Baton Refresh Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Refresh the portfolio homepage so it presents the user with stronger Korean-language positioning, promotes Baton as the lead project, and keeps Azak as an archived project.

**Architecture:** Update the single-file static homepage in place, preserving the current visual language while swapping hero copy and project card ordering/content. Add a new Baton detail page that matches the existing project detail pattern so the main card has a destination.

**Tech Stack:** Static HTML, inline CSS, existing portfolio page structure

---

### Task 1: Update homepage positioning copy

**Files:**
- Modify: `index.html`

- [ ] **Step 1: Locate hero metadata and introduction copy**
- [ ] **Step 2: Replace the meta description with the new positioning**
- [ ] **Step 3: Replace the hero title and description with the approved Korean copy**
- [ ] **Step 4: Keep the existing visual structure intact**

### Task 2: Reorder and rewrite project cards

**Files:**
- Modify: `index.html`

- [ ] **Step 1: Move Baton to the first card**
- [ ] **Step 2: Rewrite Baton card date, badge, description, and tech tags**
- [ ] **Step 3: Keep `api-lab-mcp` as the second card with accurate registry wording**
- [ ] **Step 4: Convert Azak from live positioning to archive positioning without removing it**

### Task 3: Add Baton detail page

**Files:**
- Create: `projects/baton.html`

- [ ] **Step 1: Follow the existing project detail page style**
- [ ] **Step 2: Write Korean-first content focused on governance workflow, worktree-based execution, and operational visibility**
- [ ] **Step 3: Avoid overstating original authorship; present Baton as an expanded orchestration project**
- [ ] **Step 4: Link the main card to the new page**

### Task 4: Verify output

**Files:**
- Modify: `index.html`
- Create: `projects/baton.html`

- [ ] **Step 1: Review the edited HTML for broken structure**
- [ ] **Step 2: Check git diff to verify only intended files changed**
