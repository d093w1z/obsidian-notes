### Knowledge-Based agents
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
