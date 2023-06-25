26-06-2023 @ 00:00

Status: #idea

Tags:

# Knowledge-Based Agents
knowledge and reasoning 
capabilities:
	maintain internal state
	reasoning 
	update knowledge base
	take actions

two components:
	knowledge base
	inference systems 
	
```txt
┌─────┐                     output/action
│ env │◄───────────────────────────────┐
└──┬──┘                                │
   │     ┌───────────────────────┐     │
   │     │                       │     │
   │     │ ┌─────────┐           │     │
   └─────┼─┤inference├───────────┼─────┘
   input │ │ engine  │           │
         │ └─┬─────▲─┘           │
         │   │     │  ┌────────┐ │
         │   │     │◄─┤learning│ │
         │   │     │  └────────┘ │
         │ ┌─▼─────┴─┐           │
         │ │knowledge│           │
         │ │ base    │           │
         │ └─────────┘           │
         │                       │
         └───────────────────────┘
```


---
# References