# Reflection — E-ducator Timetable System

## Objective
Build a real client-facing feature (time schedule upload) within a team, using Flutter and Supabase, while managing a shared codebase across multiple contributors.

## What I Did
I was responsible for Module 4 — the upload time schedule feature — which meant setting up Flutter from scratch on Windows, working through GitHub branch management with the team, and integrating with the Supabase backend.

## What Was Difficult
The most persistent issue was schema mismatches between what the Flutter app expected and what Supabase actually had. Because different members were working on different modules in parallel, the backend schema would shift slightly without everyone being aware — which meant debugging often started with "is this a code bug or a schema bug?" rather than going straight to the fix.

## How This Connects to Course Objectives
This reinforced a core application development lesson that's easy to skip in solo assignments: the frontend and backend need a shared, explicitly communicated contract. In a real team setting, that contract has to be actively maintained, not just designed once at the start.

## What I'd Do Differently
I'd push for the team to document schema changes in a shared place (even a simple changelog) as soon as they happen, rather than discovering mismatches through runtime errors.
