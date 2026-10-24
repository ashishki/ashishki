# English Teacher Assistant

A workflow assistant being designed with an English teacher for homework
preparation, review, delivery, booking, and administration.

**Stage — 24 October 2026:** discovery and technical design. The project has a
documented brief, integration proposals, a task graph, and sprint acceptance
criteria. Application implementation and real-account integrations have not
started; feature designs still require review and approval.

## The problem

Preparation and administration extend beyond the lesson itself. The teacher
already has teaching materials and professional judgment. The design aims to
make those resources easier to reuse while keeping homework and pedagogical
feedback under the teacher's control.

## Proposed journey

This is the intended flow, not an implemented demonstration.

1. Select material from the existing library and the learner's goals.
2. Prepare personalized homework and a faithful preview.
3. Let the teacher inspect it and request changes by text or voice.
4. Revise the draft while preserving the source exercise and required context.
5. Publish the exact approved version through the planned Miro and Google Forms
   delivery paths.

A parallel workflow covers Telegram booking, Google Calendar, reminders, and
administrative documents. Calendar and payment policy must come from the owner.

## Design choices

The proposed storage separates original assets in Google Drive from the
catalogue, exercises, extracted text, and versions in PostgreSQL. Model-assisted
work is planned through the official DeepSeek API; hosted speech recognition and
external OCR have separate capability, cost, and privacy checks.

Learning video is considered through audio/transcript and instructions first.
Frames and OCR are added when the task depends on visual meaning. Generated PDF
and board layouts still need visual inspection.

## How success will be checked

The plan has four explicit sprint acceptance checkpoints. Engineering checks,
faithful exercise reproduction, visual layout checks, and the teacher's decision
are separate evidence. A reviewer passing the code cannot approve homework.

Time savings remain a target until measured against the teacher's actual
workload. Reusable homework blueprints require repeated accepted examples;
next-lesson generation remains later work.

## Publication boundary

This summary reflects the private project's brief v13, design, README, and task
ledger inspected on 24 October 2026. It contains no learner records, teaching
corpus, private account details, or claims of a working integration.

[Back to the portfolio](../README.md)
