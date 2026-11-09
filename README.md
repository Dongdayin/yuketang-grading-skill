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

This skill is based on the user's pre-existing locally installed Codex skill named `yuketang-grading`. The local copy contained no upstream repository URL, author attribution, or license metadata, so its earlier upstream origin cannot be verified. This repository identifies that local file as its baseline and does not claim authorship of the original skill.

## Privacy

This release contains reusable workflow guidance only. It excludes student names, IDs, profile images, submission photos, scores, timestamps, course/classroom/exam identifiers, assignment links, account details, and the specific answer key from the grading session.

## License

No license is declared because the original skill's license could not be verified. Public availability does not grant permission to redistribute or relicense the original material beyond this attributed adaptation.

