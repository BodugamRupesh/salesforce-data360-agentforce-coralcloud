# 06 — Agentforce Extension with Flow Action

## Goal
Extend Agentforce using a Flow-based action that uses reservation data to assist check-in/service operations.

## Flow Details
- Flow Type: Autolaunched Flow
- Inputs: recordId / ContactId (based on configuration)
- Outputs: message/response text to Agentforce

## Steps Performed
1. Setup → Flows → New Flow (Autolaunched)
2. Created input/output variables
3. Implemented logic to fetch guest reservation details
4. Activated flow
5. Setup → Agentforce → Actions → New Action (Flow)
6. Added the action to CC Service Agent

## Screenshot Proof
- images/flow-action.png
- images/agentforce-response.png

