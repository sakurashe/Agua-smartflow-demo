# Agua SmartFlow — Interview Demo

This repository contains a simplified example used to demonstrate the connection between product requirements, development activity, and QA handover.

## Current alert behaviour

During an ongoing low-flow incident, the system may generate repeated notifications.

## Scope

Demonstration only. Not production software.

## Proposed alert behaviour

* Generate an alert after five consecutive minutes below the configured threshold.
* Suppress repeated notifications during the same active incident.
* Allow a new alert for a separate incident after recovery.

## Requires clarification

The definition of recovery must be agreed before QA can fully validate the behaviour.
