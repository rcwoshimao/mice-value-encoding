Repo for cogs 118C final project 
## Project Exploration Framework

### 1. Inspect Dataset
- Check dataframe structure and trial-level signals (`a`, `R`, `LR_Prob`, `Reaction_Time`).  
- Verify list lengths and look for missing or unusual values.  
- Confirm number of mice, sessions, and trials per session.

### 2. Define Behavioral Signals
- Encode trial-by-trial **choices**, **rewards**, **reward probabilities**, and **reaction times**.  
- Simplify or normalize signals if needed (e.g., left/right choices as 0/1).

### 3. Visualize Behavior
- Plot choice and reward sequences across trials.  
- Plot reward probability vs choice.  
- Explore patterns such as persistence, learning, or exploration.

### 5. Autocorrelation Analysis
- Compute autocorrelation of choice sequences to quantify temporal dependencies.  
- Assess whether decisions exhibit persistence or structured patterns across trials.

### 6. Cross-Correlation Analysis
- Compute cross-correlation between reward and future choice sequences.  
- Explore how past rewards influence subsequent decisions across different temporal lags.

### 7. Temporal Lag Analysis (Shortened)
- Examine correlations at a few trial lags to estimate how far past rewards influence choices.

### 8–10. Compare, Interpret, and Summarize
- Compare correlation patterns across mice and sessions.  
- Interpret results in the context of history-dependent value learning.  
- Summarize key findings: persistence in choices, influence of reward history, and temporal structure of learning.


# Auto-correlation of choice

1. Measures intrinsic persistence. (DONE)

3. If the mouse chose Right on this trial, is it more likely to choose Right again 1 trial later? 2 trials later?

2. Measure reaction time

# Cross-Correlation of reward -> future choice 
1. Missed trials v.s. rraction time 
2. Alarm trials v.s. reaction time 
3. Rewarded choice trials 

Measures reinforcement sensitivity.

“Does reward at trial t influence choice at trial t + k?”

Together, these give insight into:

Learning timescale 

Behavioral memory 

Block adaptation 
