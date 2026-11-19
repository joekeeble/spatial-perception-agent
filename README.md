# Spatial Perception & Agentic Space Monitor

Real-time computer vision and agentic prototype for understanding people, movement, and spatial events, and answering natural-language queries over live space state.

## Planned Architecture
- **Perception & Tracking (`src/perception.py`)**: Person/object detection and multi-object tracking in PyTorch, emitting structured spatial events (entries, exits, zone transitions, dwell time).
- **Spatial State (`src/state_store.py`)**: Compact, queryable representation of current space occupancy and recent transitions.
- **Agent Layer (`src/agent.py`)**: Tool-calling interface over spatial state to answer queries about room activity and trigger alerts.

## Status
Work in progress — setting up baseline detection/tracking pipeline and latency benchmarks.
