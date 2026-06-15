# Approva — Product Overview

## Identity

- **Name:** Approva
- **Type:** Marketing agency project review and approval SaaS platform
- **Tagline:** Where creative work gets reviewed, revised, and approved — fast.
- **Positioning:** Frame.io + Filestage-level collaboration for marketing agencies and their clients. Replaces scattered email chains, Slack threads, and shared drives with a single structured review workspace per project.
- **Tone:** Professional, calm, precise. Built for creative teams and their clients — not developers.

---

## Users & Roles

### Agency User
Project managers, creatives, and account managers at marketing agencies.
- Create and manage projects
- Upload deliverables and creative files
- Manage team and client assignments
- Manage review rounds
- Respond to comments and submit revisions

### Client User
Brand managers, stakeholders, and approvers on the client side.
- Review assigned projects
- Leave comments, threaded replies, and @mentions
- Create image annotation pins
- Request revisions or approve/reject deliverables
- Access only their assigned projects (project-specific access via invitation)

---

## Core Problem

Marketing agencies manage creative reviews across email chains, Slack threads, and scattered file-sharing tools. This leads to:
- Lost or duplicated feedback
- Version confusion (wrong file approved)
- Missed approval cycles
- No audit trail of who approved what and when
- Delayed project delivery

---

## Core Solution

Approva gives every project a dedicated review workspace. Agency teams upload deliverables; clients review, annotate, and decide — all in one place. Every round is tracked, every approval is timestamped, every comment is threaded and attributed.

---

## Features

### Authentication
- Email/password login
- Google OAuth
- Password reset
- Session management
- Role-based access control (Agency User, Client User)

### Project Management
- Create, edit, archive projects
- Project dashboard with status tracking
- Client and team assignment
- Project activity timeline

### Client Invitations
- Invite clients via email
- Accept-invitation workflow
- Project-specific access scoping
- Revoke and resend invitations

### Project Review Workspace
- Dedicated workspace per project
- Project overview screen
- Deliverables library
- Review status dashboard
- Review round tracking
- Approval history

### File Management
- Upload, delete, replace files
- File versioning (full version history)
- Secure file serving with expiring URLs
- Download permissions and access-controlled storage
- Drag-and-drop upload UI

### Supported File Types
- Images: PNG, JPG, SVG, WebP
- Video: MP4, MOV
- Documents: PDF, DOCX, PPTX
- Marketing assets and general attachments

### Review Workflow States
Draft → Submitted for Review → In Review → Revision Requested → Resubmitted → Approved → Rejected → Completed

### Review Rounds
- Unlimited review rounds per deliverable
- Round history, round summaries
- Per-round approval tracking and revision tracking

### Comments & Collaboration
- File-level threaded comments
- @mentions
- Reviewer attribution
- Comment editing and deletion
- Resolve/unresolve comments
- Comment notifications

### Annotations (Images)
- Coordinate-based annotation pins on images
- Annotation comments and status
- Visual comment indicators on canvas

### Video Review
- In-player video review with timestamp comments
- Timeline markers and frame-specific feedback
- Video discussion threads

### Document Review
- Inline PDF viewer
- Page-specific comments and comment anchors

### Approval System
- Approve, request revisions, or reject per deliverable
- Approval notes and timestamps
- Final approval records and full approval history

### Notifications
- New file uploaded
- Review requested
- Comment added / reply received
- Revision requested
- Approval completed
- Project updates

### Dashboards

**Agency Dashboard:** Active projects, pending reviews, approval status, revision requests, client activity

**Client Dashboard:** Assigned projects, pending reviews, awaiting approval, recent activity

### Public Submission
- Public upload forms for external submissions
- Supports images, videos, documents, attachments
- Secure storage with upload validation

---

## Technical Architecture
- **Stack:** Remix (Vite) + Express + MongoDB (Mongoose/Typegoose) + TypeScript
- **Styling:** Tailwind CSS + shadcn/ui
- **Auth:** Email/password + Google OAuth, session management, RBAC
- **File Storage:** Secure, access-controlled, expiring URLs
- **Real-time:** Live comments and notifications
- **Audit:** Full activity logs and audit trails
- **Architecture:** Production-ready SaaS, full frontend + backend, complete database schema

---

## UX Reference
Designed to feel like Frame.io, Filestage, and Figma's review mode. Modern SaaS aesthetic — clean, fast, responsive. Desktop and mobile layouts.

---

## Branding
- **Primary color:** Indigo (#4F46E5)
- **Accent:** Emerald (#10B981) — used for approved states and positive actions
- **Danger:** Rose (#F43F5E) — used for rejections and critical alerts
- **Background:** White / slate-50
- **Type:** Dark (slate-800/900) on light backgrounds
