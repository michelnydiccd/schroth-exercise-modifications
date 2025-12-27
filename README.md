# Schroth Exercise Modification Library

A collaborative, open-source library for Schroth Method exercise modifications. This library allows physiotherapists to share, review, and refine adaptations for specific patient presentations, enhancing collective clinical knowledge and patient care.

## Purpose

The Schroth Method is highly individualized. A patient's ability to perform a standard exercise can be limited by factors like curve type, pain, hypermobility, or comorbidities. This centralized, version-controlled repository allows for systematic documentation and peer review of these valuable clinical modifications, which are often not found in textbooks.

## How to Contribute

We welcome contributions from physiotherapists, Schroth practitioners, and rehabilitation professionals. To submit a modification:

1. **Create an Issue:** Open a new GitHub issue describing the clinical scenario, patient limitation, and the exercise needing adaptation. Use the title format: `Request: Modification for [Exercise Name] in a Patient with [Condition/Limitation]`.

2. **Fork the Repository** (or create a branch if you have write access) and create a new file in the `modifications/` directory.

3. **File Naming Convention:** Use the format `[curve-type]-[exercise-name]-[modification-description].md`. For example: `thoracic-curve-muscle-cylinder-shoulder-mod.md`.

4. **File Content Template:** Each modification file should follow this structure:

   ```markdown
   # Modification: [Exercise Name]
   ## Original Exercise
   - **Name:** [Original exercise name]
   - **Standard Indication:** [Brief description of the standard exercise]

   ## Clinical Rationale for Modification
   - **Patient Presentation:** [Describe the patient's specific limitation, e.g., shoulder impingement, hypermobility, pain]
   - **Rationale:** [Why the standard exercise is not suitable and how this modification addresses the issue]

   ## Modified Exercise Instructions
   1. **Starting Position:** [Detailed description]
   2. **Movement Sequence:** [Step-by-step instructions]
   3. **Visual/Verbal Cues:** [Key cues for the patient]
   4. **Breathing Coordination:** [If applicable]

   ## Key Clinical Reminders
   - [Important points to ensure safety and effectiveness]
   - [Common errors to avoid]
   - [Progression/Regression options]

   ## Contributor
   - [Your name/clinic, optional contact info]

   ## Version History
   - v1.0.0 (YYYY-MM-DD): Initial submission
   ```

5. **Open a Pull Request:** Link your PR to the relevant issue by including "resolves #[issue-number]" in the PR description.

6. **Peer Review:** Other clinicians will review your submission, suggest refinements, and approve the merge.

## Review Guidelines

When reviewing a modification, consider:
- Clinical safety and appropriateness
- Clarity of instructions
- Alignment with Schroth principles
- Potential for generalization to similar patient presentations

## License

All contributions are licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). By contributing, you agree to license your work under this license.

## Contact

For questions or suggestions, please open an issue or contact the repository maintainers.

---

*This library is maintained by a community of Schroth practitioners. Always consult with a certified Schroth therapist before applying any modifications in clinical practice.*