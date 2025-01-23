
In a waterfall model, the product is not released until the project is done.

## Staged Delivery Model
In the staged delivery model, the product is released in stages / increments.

The planning, requirements analysis and architectural design is still linear, but the releases are delivered in stages.

Advantages to this life cycle model:
- Customer will see functionality earlier than the waterfall model
- If the project runs out of budget, at least the project has some features available, unlike the waterfall model where it is all or nothing.
- Tangible progress is made, because actual software is delivered at each release

Disadvantages:
- Project must be planned very carefully by management.
- Each delivery and release, must not be dependent on each other. Dependencies must be minimized
	- If a delivery is dependent on another delivery, that delivery cannot start until all dependencies are stratified.

![[Staged Delivery Model.png]]

## Design-to-Schedule Model

Most software vendors use this.

Similar to the staged delivery model.

Most important features, that are higher in priority are done first.

In this model, we don't know how many releases will be delivered.

Requires good management, and that project features are prioritized.

Main disadvantages, if we don't finish by the deadline, then we have wasted some time in planning phases.

![[Design to Schedule Model.png]]

## Life Cycle Model Scorecard

| Life Cycle Model Capability                      | Staged Delivery | Design to Schedule |     |
| ------------------------------------------------ | --------------- | ------------------ | --- |
| Works with poorly understood requirements        | Poor            | Poor - Fail        |     |
| Produces Highly Reliable System                  | Excellent       | Fail               |     |
| Produces expandable System                       | Excellent       | Fail - Excellent   |     |
| Manages Risks                                    | Fail            | Fail - Excellent   |     |
| Can be constrained to pre-defined schedule       | Fail            | Excellent          |     |
| Has low overhead                                 | Fail            | Fail               |     |
| Allows for mid-course corrections                | Poor            | Poor - Fail        |     |
| Provides customer with progress visibility       | Fail            | Fail - Good        |     |
| Provides management with progress visibility     | Excellent       | Excellent          |     |
| Requires little manager/developer sophistication | Fail            | Poor               |     |
