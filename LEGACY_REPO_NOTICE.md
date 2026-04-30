# Legacy Repository Notice

This repo is now treated as a legacy/reference dashboard repository for Hanna.

## Canonical nurse dashboard

Use this repo for active nurse command center work:

`farhaned07/hanna-nurse-dashboard`

Target domain:

`nurse.hanna.care`

## Why this repo is legacy

There are two dashboard repos:

- `hanna-dashboard`
- `hanna-nurse-dashboard`

To reduce product and deployment confusion, Hanna will use `hanna-nurse-dashboard` as the canonical Nurse Command Center going forward.

## Current product rule

Do not add new sprint functionality here unless intentionally migrating old code into the canonical dashboard repo.

All active dashboard work should support this care intelligence loop:

`Documentation -> Care Plan -> LINE Follow-up -> Risk Signal -> Nurse Priority Queue -> Report`
