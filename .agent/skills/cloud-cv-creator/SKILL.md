---
name: cloud-cv-creator
description: Comprehensive assistant for creating, refining, and formatting CVs/Resumes specifically for Cloud Engineers and Cloud Architects. Use when the user wants to write a resume for a cloud role, needs suggestions for cloud skills/keywords, or wants to format a cloud engineering CV.
---

# Cloud CV Creator

## Workflow

1.  **Analyze Request**: Determine if the user needs a full CV creation, specific content suggestions, or formatting help.
    *   *Target Role*: Cloud Engineer, Cloud Architect, DevOps Engineer, SRE.
    *   *Target Platform*: AWS, Azure, GCP, or Hybrid/Multi-cloud.

2.  **Use Templates**:
    *   For structure, use the template in `assets/cv_template.md`.
    *   Copy sections as needed to build the document.

3.  **Draft Content**:
    *   Use `references/cloud_competencies.md` to identify relevant keywords, skills, and action verbs.
    *   Ensure the "Professional Summary" highlights architectural experience or engineering depth appropriate to the specific role.
    *   Focus on **quantifiable results** (e.g., "Reduced costs by 30%","Improved deployment speed by 50%").

4.  **Refine & Polish**:
    *   Check for consistent terminology (e.g., "AWS Lambda" vs "Lambda").
    *   Verify checking of proper capitalization for tools (e.g., "Kubernetes" not "kubernetes", "Terraform" not "terraform").

## References
- **Competencies & Keywords**: See [cloud_competencies.md](references/cloud_competencies.md) for lists of skills, certifications, and example bullet points.

## Assets
- **CV Template**: See [cv_template.md](assets/cv_template.md) for a standard markdown structure.
