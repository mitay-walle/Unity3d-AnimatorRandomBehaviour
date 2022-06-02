# Unity3d-AnimatorRandomBehaviour
Plays random animation state from Animator.StateMachine
# Pros
- No need to use Animator.parameters
- list of animations is updated automaticly at OnBeforeSerialize()
# Cons
- use Animator.Crossfade(stateNameHash) to switch animation
# How to use
- Create Animator.StateMachine, add to it states with your random animation
- Make from all states transitions to exit
- Add AnimatorRandomBehavior to stateMachine
- set reference to RuntimeAnimatorController
- save
