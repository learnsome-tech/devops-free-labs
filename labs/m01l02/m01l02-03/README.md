# m01l02-03 · Reading deployments out of a repository

**Lesson:** [Throughput: Change Lead Time And Deployment Frequency](https://learnsome.tech/learn/devops-course/m01l02) (lesson 1.2, module 1: Measurement And Outcomes: DORA) · Free  
**Check:** Read along

## Goal

You can define change lead time and deployment frequency in DORA's own words, say what each one excludes, and compute both from a real git history rather than from a survey answer.

## Files

- [`starter/dora_metrics.py`](starter/dora_metrics.py): the listing from the lesson
- [`check.json`](check.json): how `./check` runs and checks this lab

## Steps

1. Read `starter/dora_metrics.py` alongside the lesson.
2. Follow it the way the lesson builds it:
   - Lines 1–5: every tag whose name begins
   - Lines 6–12: the range between two tags
   - Lines 13–19: one record per deployment
3. Notes from the lesson:
   - Line 3: tagger date, not commit date: when it shipped
   - Line 10: the commits this deployment carried and no earlier one

## How to check

**Read along.** It is a listing to read alongside the lesson, not a program to run.

There is nothing to check: `./check m01l02-03` says so and moves on.

---

[Open the lesson on LearnSome.tech](https://learnsome.tech/learn/devops-course/m01l02) · [All labs of this lesson](../README.md) · [Course README](../../../README.md)
