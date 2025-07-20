# Openln

An open‑source organization building tools for self‑learners. We’re starting with a goal‑driven learning engine and will add evaluation, certification, and contribution modules next.

---

## What Is Openln?

Openln helps you:

1. **Set a clear learning goal**  
2. **Follow a step‑by‑step plan**  
3. **Get work evaluated against public rubrics**  
4. **Earn free, shareable certificates**  

All code is public. You can see exactly how each piece works and join in to help build it.

---

## Project Modules and Status

| Module                  | Status          | Next Steps                                      |
|-------------------------|-----------------|-------------------------------------------------|
| **goal-engine**         | In development  | Finish plan generation and progress tracking    |
| **rubric-evaluator**    | Yet to start    | Define API, create example rubric and test case |
| **certify-api**         | Yet to start    | Design certificate format and PDF generator     |
| **openln-platform**     | Yet to start    | Build basic UI, connect to engine & APIs        |
| **openln-contribute**   | Yet to start    | Create templates for community‑made modules     |
| **docs**                | Basic outline   | Add setup guides, architecture diagrams         |
| **org-website**         | Planning        | Draft homepage content and design               |

---

## How to Help

1. **Choose a module** from the list above.  
2. **Fork** its repository, then clone and run it locally:  
   ```bash
   git clone https://github.com/openln/<repo-name>.git
   cd <repo-name>
   npm install
   npm run dev
