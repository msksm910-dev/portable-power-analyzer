# portable-power-analyzer
A diagnostic tool analyzing portable power station               failure patterns from Reddit data
# Portable Power Analyzer

## Overview
A tool that collects and analyzes publicly available Reddit 
comments about portable power stations (EcoFlow, Jackery, Anker) 
to identify common failure patterns.

## Purpose
- Read-only data collection from relevant subreddits
- AI-based failure pattern classification
- Powers a Japanese-language product diagnosis tool

## Target Subreddits
- r/preppers
- r/camping
- r/ecoflow
- r/jackery
- r/solar

## Tech Stack
- Python (data collection)
- Anthropic Claude API (pattern classification)
- Next.js (frontend diagnosis tool)

## Data Usage
- No individual user data is stored
- Only aggregated failure patterns are retained
- All data is publicly available on Reddit
