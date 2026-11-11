# Workflow Audit

This page shows how the four pillars of a tidy GitHub workflow fit together: **branch**, **pull request**, **issue**, and **close-out**.

## Branch

A branch is an isolated line of development. Work starts on a feature branch (e.g. `feature/audit-notes`) rather than directly on `main`, so the default branch stays stable and每一次 change is reviewable.

## Pull Request

A pull request (PR) is the conversation about moving changes from a feature branch into the default branch. It ties the branch to human review: diff, comments, checks, and approval. In this demo, PR #1 — *"Add workflow audit notes"* — carries the write-up from `feature/audit-notes` into `main`. It is intentionally left open so the team can see a live, unmerged PR in action.

## Issue

An issue is where the *why* lives: the checklist, the ticket, the tracked follow-up. Here, issue #1 — *"Demo: workflow checklist"* — captures the demo task, and issue #2 is attached as a sub-issue to show how a checklist decomposes into smaller work items.

## Close-Out

Close-out is the ritual that makes the workflow tidy:

1. **Review** the PR (line-level comments, CI checks).
2. **Merge** or **close** the PR — here we leave it open as a demo artifact.
3. **Resolve** the checklist issue with a comment (*"Checklist complete, closing this out"*) and mark it **completed**.
4. **Keep** the follow-up issue open until its own work is done.

The result: every change is traceable from branch → PR → issue → close-out, with ownership recorded in the **Owner** section below.

## Owner

| Field | Value |
| --- | --- |
| **Login** | HeziLiu |
| **Display name** | Hezi Liu |
| **Bio** | treat me like a tree |
| **Location** | Beijing/Guiyang |
| **Company** | BUPT/GZU |
| **Profile** | https://github.com/HeziLiu |
