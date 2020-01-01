# Quonauts 6 — Proposals

<a name='1'/>

## #1 — Failed

Quonauts 6 ends immediately and Quonauts 1 starts all over again.

<a name='2'/>

## #2 — Passed

Create a rule section within `Roles` named `Rule offender`:
> Any player which has 1 or more strikes gains the rule offender role. Rule offenders cannot participate in the game (perform any game actions). After 24 hours, a players strike count will decrease by 1, if above 0. If a players strike count is 0, the Rule Offender role will be removed.

<a name='3'/>

## #3 — Passed

Create a rule section after "Modifying proposals" named "Disallowed in proposals" (this proposal depends on proposal #2):
> Proposals may not give any players any more power than others. An exception to this rule is the Rule Offender role, and any power gained via some form of quantity.
> 
> Power here is defined as the abillity to do some game action, or having more abillity to do some game action than others, or being able to win the game. (e.g "Sinthorion wins the game." breaks this rule, but "Any player with 1000000 moon cheese or more wins the game." does not.)

<a name='4'/>

## #4 — Passed

Out of Game Information

Create rule #9, named “Out of Game Information”

> Out of game information is any information that exists outside of the confines and variables of the game. This information includes but is not limited to:
> The player’s username, presence on the internet, and messages in other channels or servers.
> Some examples of *In Game Information* are the players votes, player’s quantities, proposals, or messages sent in the Quonauts 6 category.

<a name='5'/>

## #5 — Passed

Append the following to rule 5.3:

> The player passing the proposal may choose to add or remove whitespace and fix typos or grammar mistakes as needed so long as the meaning of the proposal remains unchanged. Clarifications or additional details should always be added by means of a new proposal.

<a name='6'/>

## #6 — Failed

Alternative to proposal #3, the purpose of this proposal is to ensure more freedom while protecting minorities from unfair majority rulings.

This proposal depends on proposal #2 and proposal #4. If this proposal passes, any effects of proposal #3 will be retroactively undone and overwritten by this proposal.

Create a rule section after "Modifying proposals" named "Disallowed in proposals"

> Proposals may not create an unfair advantage for minorities based on Out of Game Information. Wether this has occurred can be determined through a formal poll, and the effects will be undone as necessary.

<a name='7'/>

## #7 — Passed

Create a rule section after "<#660555000296112128>" named "#transactions"
> The #transactions channel may be used to modify quantities, but only as the game rules allow quantities to be changed.

<a name='8'/>

## #8 — Passed

Overwrite the rule section "Quantities" with the following:
> A quantity is a named property with a numerical value for each player.
> 
> By default any unique quantity added to the game:
> 
> • applies to all players
> • is instantiated at zero
> • must always be an integer
> • must never have a negative value
> • cannot be traded or exchanged
> 
> The following quantities exist:
> 
> • Strike
> • Point

<a name='9'/>

## #9 — Passed

This proposal depends on proposal #8.
Append the following to the rule section "Closing Proposals":
> When a proposal is closed, if the proposal has passed then the author of the proposal gains 2 points.
> When a proposal is closed and has been FULLY passed (i.e the player has updated the <#660455454429937713> channel if needed, or done whatever action is required to the best of their ability) then the player who passed the proposal gains 1 point.

<a name='10'/>

## #10 — Failed

Append the following to the rule section "<#660455405738262549>":
> If a message stating "i win" is present in the <#660455405738262549> channel, the author is the winner of the game.

<a name='11'/>

## #11 — Passed

Append to rule 1.4.3:
> Additionally, the offending player loses 5 points. If they have less than 5 points left, they lose as many as they have instead.

<a name='12'/>

## #12 — Passed

Trying to clean up the initial ruleset a bit

Move rule 5.4 "Passing and failing proposals" to rule 5.3.1 (subsection of 5.3 "Closing proposals"), and append the following:

> The player that authored a proposal may fail or delete it at any time.
> 
> When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability.

Remove from rule 5.3:

> The player that authored a proposal may fail or delete it at any time.
> 
> When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability.

<a name='13'/>

## #13 — Deleted

<a name='14'/>

## #14 — Passed

Create a new rule at the end of the ruleset (the rule number assigned to this rule will henceforth be referred to as `x`) named “Space”, with the following content:

> “Space” is a Tensor of order 3 (a 3 dimensional array). All players have a position in space, a set of 3 integers which denote the position in 3D space, which can be written with the following notation: `[x,y,z]`.

Create another rule, number x.1, named “Center” with the following content:

> All player’s positions are initialized at [0,0,0], which can also be referred to as the “center”

Create another rule, number x.2, named “Movement” with the following content:

> Once every 23 hours (in other words, as long as the player has not moved in the last 23 hours) a player may modify their personal position in space by +1 or -1 in all or some of the axis’. (ex. [2,3,-1] > [2,2,0] is valid).

Create another rule, number x.3, named “Restrictions” with the following content:

> halfArea is equal to 3
> Positions on any of three axis must be between negative halfArea and positive halfArea. An axis of a position may not be changed in a way that is not allowed by this rule.

<a name='15'/>

## #15 — Deleted

<a name='16'/>

## #16

Change the "quantities" rule section, renaming "Points" to "Blue Points" and creating a new quantity named "Red Points", and stating that all usage of "points" refers to "Blue Points" unless otherwise specified.

<a name='17'/>

## #17

Add a new rule named "Multicoloured points".
> Players may, at any time, create any currency following the name pattern xxx-xxx-xxx-points.
> xxx-xxx-xxx must correspond to 3 positive integers between 0 and 255 inclusive.
> 255-000-000 points are identical to the currency Red Points, and thus should not be created.

<a name='18'/>

## #18

This proposal depends on proposal #17.
Add a new rule named "Values of coloured points".
> The value of any given point colour is equal to `((r+g+b)/3)/255` 255-255-255-points(effectively, the brighter the currency, the higher the value). 000-000-000-points, however, are worth `sin(h)+1.1` 255-255-255-points where h is the current hour in UTC+x, where x is the last 2 digits of the current year in UTC. If transferring from one currency to another, the points added to the latter are equal to` points-deducted-from-former*(former_value/latter_value)`.

<a name='19'/>

## #19 — Passed

As a New Year gift, every player receives one point!

<a name='20'/>

## #20

Create a new rule #10.4 named “Claiming Space”, with the following content:

> "Claiming" is an event in which a certain position in space becomes the property of a specific player. Claiming may occur in multiple ways.

Create rule #10.4.1, named "Movement Claiming" with the following content:

> When a player leaves a position in space to move into a new one, the position they were previously in becomes claimed by the player so long as it was not claimed before. Otherwise, they must pay 1 point to the previous owner of the position to claim it.

Additionally, add a new rule, #2.6, named "#position-claims", with the following content:

> When a player claims any position in space, the claim should be logged clearly and concisely in this channel.

<a name='21'/>

## #21

Append the following text to the end of the rule created by proposal #17:

> The 3 positive integers may be referred to respectively as "Red", "Green" and "Blue".

Add a new rule dependent on proposal #18 named "Dominant Color" with the following content:

> All points have a dominant color and may be manipulated based on their dominant color in some situations.
> 
> The highest number in their value (ex. `200` in `200-69-42-points`) becomes the dominant color. If the point has multiple equal highest valued numbers, the dominant color defaults to the number furthest left in the notation (ex. `8, 255, 255` has a dominant color of Green (or the second number))

<a name='22'/>

## #22

In my opinion if the point has two equal highest valued numbers the dominant color is the one that is lower. This eliminates bias towards the red side. And if the numbers are all equal there is no dominant color.
Example:
(0,255,255) -> red

<a name='23'/>

## #23

(This rule is why I wrote the whole dominant color thing)

Add the following text to the end of rule 10.3:

Players may not move into a position owned by another player unless they have more points of at least two dominant colors than that player, in which case they may move into the other player's claimed position.

