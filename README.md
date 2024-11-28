# StatusEffects

To use this plugin add it to the player character,

To activate the status effects you need to add "BPI_ActiveStatusEffect" to the player AND the actor that is activating the effect.

Also make sure that "BPI_ActiveStatusEffect" is added to "AC_StatusEffects" otherwise it will not work.

Then you need to add the call event node for the effect you want to activate, with the target being "BPI_ActiveStatusEffect"

Then you need to get a reference to your character, use a "get component by class node" and set the component to "AC_StatusEffects"

Link the return with the target of the status effect node.

And you should be able to activate the status effect from that object. 




IF THIS DOESN'T WORK, OR YOU ENCOUNTER ANY BUGS PLEASE CONTACT ME HERE:  S3060220@tees.ac.uk
