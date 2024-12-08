## Model Description
**Input:** 2D spin configurations and temperatures.  
**Output:** Classifications (low-temperature, critical temperature, high-temperature states).  
**Architecture:** CNN with 3 convolutional layers and 2 fully connected layers.

## Performance
- Accuracy: 92% on test data.
- F1-score: 0.89 for critical states.
- Metrics evaluated on 10% holdout test set.

## Limitations
- Model trained on 2D configurations; may not generalize to 3D systems.

## Trade-offs
- High accuracy near critical points, but less effective in very high-temperature regimes.

