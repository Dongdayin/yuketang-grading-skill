# yuketang-grading

A Codex skill for reviewing and grading subjective assignments in Rain Classroom (雨课堂).

## What changed in this release

This update records reusable lessons from an anonymized grading workflow:

- Read the official answer and prior teacher marks before deciding scores.
- Check each answer step and each submitted image attachment.
- Put large, legible checks beside correct work and circles beside errors without covering the writing; undo and redraw marks that point to the wrong step or obscure the answer.
- Use short, natural teacher comments that identify the actual issue.
- Leave comments blank for full-score and unanswered work under the current teacher preference.
- Verify the saved score, comment, and marks on every image separately; leave unreadable or unavailable images marked for follow-up.
- Wait for the answer and attachments to finish loading before treating an answer as blank; a broken or black annotation preview does not prove that marks were saved.
- Keep personal student information and course-specific answer keys out of public skill examples.

## Install

Copy this folder to your Codex skills directory as `yuketang-grading`, then start a new Codex chat. The required entry point is `SKILL.md`; `agents/openai.yaml` supplies the display name.

## Source and attribution

The [originally installed Rain Classroom skill](ORIGINAL_SKILL.md) is archived here so the starting point of this supplement can be inspected. It was created locally for the user on 2026-11-04 with Codex's `skill-creator` initializer and then filled in with Rain Classroom grading guidance. It was **not installed from an external GitHub repository**. The current [SKILL.md](SKILL.md) extends that local skill with the grading details learned later. The archived text contains general instructions only; no student work is included.

## Privacy

This release contains reusable workflow guidance only. It excludes student names, IDs, profile images, submission photos, scores, timestamps, course/classroom/exam identifiers, assignment links, account details, and the specific answer key from the grading session.

## License

No license has been declared for this repository.

