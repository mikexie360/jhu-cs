# Sequential Life Cycle Model

## Pure Waterfall Model

Doing things in order in terms of time.

1. Start with planning and definitions
2. Go into Requirements Analysis
3. Design
4. Code and Unit Test
5. Format Test
6. Implement
7. Continue

Usually, one or more artifact is produced at each phase.
Usually there is one review at the end of the phase.

Sometimes a project continues to the next phase, even though there are issues with previous phases. This increases cost and time/schedule.

The further downstream a project is, the more phases a project has completed, the harder it is to go back to previous phases.
*Similar to how salmon have to expend a lot of stream to go back up river.*

Momentum problems: The farther you are down in a project using the waterfall lifecycle, the more costly it is to go back to previous phases.

![[Pure Waterfall Model.png]]
## Modified Waterfall Model

Similar to pure waterfall model

Has checkpoints at every phase of the project, with an understanding that work may have to be redone in a previous project phase.

The idea is to mitigate some momentum problems, and to make it easier to make changes.

![[Modified Waterfall Model.png]]

Life Cycle Model Scorecard

| Life Cycle Model Capability                      | Pure Waterfall | Modified Waterfall |
| ------------------------------------------------ | -------------- | ------------------ |
| Works with poorly understood requirements        | Poor           | Fail - Excellent   |
| Produces highly reliable system                  | Excellent      | Excellent          |
| Produces expandable system                       | Excellent      | Excellent          |
| Manages risks                                    | Poor           | Fail               |
| Can be constrained to pre-defined schedule       | Fail           | Fail               |
| Has Low overhead                                 | Poor           | Excellent          |
| Allows for mid-course corrections                | Poor           | Fail               |
| Provides customer with progress visibility       | Poor           | Fail               |
| Provides management with progress visibility     | Fail           | Fail - Excellent   |
| Requires little manager/developer sophistication | Fail           | Poor - Fail        |


