# Mechanisms for Enforcing Authorisation and Usage-Control Policies in LLM Agents

## Overview
Large language model agents increasingly act autonomously, plan tasks, invoke tools, and trigger external effects. This creates significant challenges in trust, safety, and policy enforcement. A model may produce a plausible action, but it must still satisfy explicit authorisation, usage-control, and obligation constraints before any consequential action is allowed.

This research proposal investigates how AI-derived semantic context can be integrated with formal runtime enforcement for LLM-based agents. The goal is to allow AI to contribute contextual understanding while preserving a clearly defined source of authority: the policy engine and runtime enforcement layer.

## Research Motivation
AI systems are increasingly used as decision-support and tool-using agents. As these systems become more autonomous, the problem is not only whether they can perform a task, but whether they can do so safely, reliably, and in compliance with policy and authorisation constraints.

This is especially important in tool-using, multi-agent, and long-horizon workflows where actions may be:
- ambiguous
- context-sensitive
- dependent on state
- subject to obligation or revocation
- externally consequential

## Core Research Question
How can AI-derived semantic context be used as bounded, fallible evidence in authorisation and usage-control mechanisms without allowing the AI component to become the authority source?

## Research Focus
This proposal explores a hybrid approach in which:
- AI interprets task context, action relevance, and uncertainty
- a deterministic policy engine evaluates authorisation, obligations, and constraints
- a runtime enforcement layer mediates external actions
- formal methods analyse selected safety and invariant properties

## Key Ideas
- AI supports contextual understanding and semantic interpretation.
- Policy and runtime enforcement remain authoritative.
- The AI component does not grant permissions or override policy decisions.
- Usage-control concepts such as mutable state, revocation, obligations, and effect-binding are central.
- Formal reasoning helps analyse safety and consistency under concurrency and state change.

## Research Objectives
1. Investigate how AI-derived semantic signals can improve task-appropriate authorisation.
2. Define a bounded policy and runtime enforcement model for LLM agents.
3. Examine usage-control principles such as obligations, revocation, and mutable state.
4. Study how these systems behave in multi-agent and tool-using workflows.
5. Compare hybrid enforcement with deterministic-only and semantic-only baselines.

## Methodological Direction
The project will combine:
- applied AI for semantic interpretation
- formal policy design and invariant analysis
- runtime enforcement of consequential actions
- comparative evaluation in bounded multi-agent scenarios

The work will emphasise the distinction between:
- semantic evidence
- formal enforcement
- policy authority
- externally visible action

## Relevance to Trustworthy AI
This research is aligned with trustworthy AI, AI safety, secure autonomous systems, and policy-aware AI. It contributes to understanding how autonomous systems can remain useful while being governed by explicit, verifiable constraints.

## Expected Contribution
This work aims to contribute to:
- secure autonomous AI systems
- trustworthy agent design
- safe tool use and bounded autonomy
- policy-aware AI decision-making
- hybrid AI + formal methods for agent security

---
