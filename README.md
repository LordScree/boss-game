# boss-game
Playing with an idea a friend had...

Game for 1-5 players (see rules for solo play variant).

## Dev notes
 * IG is keen for this to be an educational game.
 * OC is keen to make it fun to play.
 * Together, we will produce something that is <strike>neither</strike> awesome!

# The object of the game
TODO: Why are we playing?

# How to win
TODO: What is/are the end-game condition/s? How is the winner determined?

### Ideas so far...

 * Reach a victory point limit?
 * Projects completed?
 * Reach a maximum skill threshold?
 * Number of turns?

# Components

 - 1 first player marker
 - X $ (money) tokens
 - X T (time) tokens (NOTE: Unsure if time tokens are needed, could work of capacity instead)
 - X event cards
 - X project cards
 - X issue cards
 - X worker cards
 - 5 starting worker cards
 - 1 Conference Table (game board)
 - X idea tokens

# Types of card
## Event

Possibly different colour of events (e.g. red/orange/green).
## Project

### Example project card

Projects are the business' bread and butter. Completing projects gains the Boss _victory points_, which count towards winning the game. Completed projects often have lasting effects that can make it easier to overcome issues or respond to random events.

Companies should be geared towards completing as many projects as possible in a short space of time. In order to achieve this, the Boss will need to get their organisation in shape - hiring the right people and employing them in the right place. The Boss should also only bid for the best projects - some projects might not be worth the time or cost to complete them!

 - Name (flavour text)
 - Description (flavour text - something funny)
 - Costs
    - Time to setup: \[T\]
    - \[T\] per round (from capacity): \[T\]
    - $ per round to produce (overheads): \[$\]\[$\]
 - Rounds: 3
 - Reward
    - Financial return: \[$\]\[$\]\[$\]\[$\]\[$\]\[$\]
    - Special effect: Skill 5+; reduce Rounds to 1.
 - Lasting effects (once completed)
    - R&D Bonus: +3
    - Victory Points: 1

NOTE: STEM "project type"
Project bonus T on recruitment.

## Issue
## Worker
 
### Example worker card
 - Name (flavour text)
 - Background (flavour text - e.g. something funny)
 - Costs
    - Time to train: \[T\]\[T\]
    - $ per round to retain (salary) \[$\]\[$\]\[$\]
 - Outputs
    - Productivity \[ \]\[ \]\[\*\]\[\*\]
    - Skill \[ \]\[ \]\[ \]\[\*\]
    - Leadership \[ \]\[ \]\[\*\]
    - Morale: :) :) :)

NOTE: Bonuses (\[\*\]) can be unlocked via various in-game effects. Each bonus is either all locked or all unlocked (i.e. they can never be half locked).

NOTE: Morale is a special value that can affect events and issues and influence ideas.

# Ideas
TODO: No idea.

# Starting the game
1. Place the Conference Table in easy view of all players.
1. Shuffle the Event cards, Project cards, Issue cards and Worker cards and place them on the Conference Table in the designated spaces.
1. Each player starts with the following:
    1. Five $ coins.
    1. Five T tokens.
    1. A starting worker (these are all the same).
1. Randomly determine the starting player. This player receives the 1st player marker.

HOW TO MAKE SOME OF THE BUSINESS CLOSED!?!

# A game round

 1. Hiring round
    1. Draw and reveal N+1 workers (where N is the number of players). So, for a 3-player game, draw 4 workers.
        1. If there are not sufficient workers to draw, shuffle the worker discard pile to continue drawing.
            1. If there is no worker discard pile to shuffle at this point, the worker pool this round is limited to the number of remaining workers.
    1. Players bid for workers with $ and T.
        1. The $ is used to determine pick order and the T is used to hire workers.
            1. NOTE: Workers cost T to hire (this represents the amount of time it takes to train the worker).
            1. The amount of T bid must equal or exceed the amount of T required to hire a worker in order to hire that worker.
        1. Players secretly pick an amount of $ and T to bid.
        1. Players reveal $ at the same time (after revealing, players may not change their bids).
        1. The player with the highest $ bid has first pick of a worker. They are followed by the player with the second-highest $ bid, etc. until all players have selected a worker, or passed.
        1. In the event of a tie in $ bid, the player with the highest total skill picks first.
            1. In the event of a tie in skill, the player with the 1st player marker goes first.
        1. Once a player passes, they may not pick a worker again this round.
        1. After all players have picked a worker, the player with the highest bid may pick a second worker or pass, and so on until all workers have been chosen or all players have passed.
    1. The amount of $ bid is spent, regardless of whether or not a worker is hired this turn and regardless of the number of workers hired this turn.
    1. The amount of T bid is also spent this turn. The only exception to this is if no workers were hired, in which case, T is returned to the player. (If *any* workers were hired, that player receives *no* T back this turn).
    1. Any workers hired in this round are set aside until the Organisation phase (next).
    1. Place any workers not hired this turn in a worker discard pile.

1. Organisation phase
    1. All players may restructure their organisations.
    1. This round is performed simultaneously.
    1. Players wait until all players have finished reorganisation before moving onto the next phase.
    1. Restructuring follows these rules:
        1. Workers purchased this Hiring phase can be brought in at any level of the organisation. However, their bonuses cannot be unlocked this turn.
        1. If a worker hired this round becomes the CEO, see CEO for additional rules.
        1. If any worker is _promoted_ to a boss (workers are placed beneath them, where previously they had none), each of their new subordinates' bonus outputs will be locked this turn and cannot be unlocked this turn.
        1. Any worker that is _demoted_ (they had workers beneath them in the previous turn and not have none) will have all their bonuses locked this turn. Their bonuses cannto be unlocked this turn. In addition, their skill and productivity will be reduced by 1 this turn (to a minimum of 0).
    1. At the end of restructuring, resolve the following effects, working from the top of the organisation, down:
        1. Resolve CEO effects (see CEO).
        1. If a boss has just the right number of workers:
            1. They unlock the bonus skill level for this turn, if able.
            1. Each worker under them unlocks their bonus productivity, skill and leadership levels this turn, if able.
        1. If a boss has too many workers:
            1. Their productivity level is reduced by 1 for each worker over their limit (to a minimum of 0) for this turn.
            1. Each worker under them has their productivity bonus locked for this turn.
    1. Any effects that cause outputs to lock or unlock do no stack (bonuses are either locked or unlocked).
    1. Any effects that cause outputs to be locked overrides any that would cause outputs to be unlocked (i.e. locking takes priority).
    1. Any effects that cause skill levels to be reduced _do_ stack.
    1. If combined effects would cause a worker's output to be unlocked _and_ reduced, the bonus outputs are not unlocked. Thus, any reduction in output prohibits the use of bonus output levels this turn.
    1. Outputs can never be below 0.

TODO: Consider promotion/demotion rules. Technically, if the organisation is structured such that a whole new layer is introduced above the worker, they have been demoted, right?

NOTE: Possibly:
 - Draw resource drain cards / morale cards from restructure.
 - Morale not yet considered...
 - Effects are affected by team "colour" or DISC value, etc - possibly different variations of the game could teach different subtleties.

1. Event phase
    1. The Event for this round is drawn. This is a random event that affects all players.
        1. Some events may have an immediate effect, some may affect one thing for a period of time.
        1. Events last for as long as they state. Some have an ending condition.
    1. Resolve any immediate effects now.

1. Project phase
    1. Draw and reveal N+1 projects (where N is the number of players). So, for a 3-player game, draw 4 projects.
        1. If there are not sufficient projects to draw, shuffle the project discard pile to continue drawing.
            1. If, after shuffling the project discard pile, there are still not enough projects for this round, the game ends immediately.
    1. Players bid for projects with $.
        1. Players secretly pick an amount of $ to bid.
        1. Players reveal $ at the same time.
        1. The player with the highest bid has first pick of a project. They are followed by the player with the second-highest bid, etc. until all players have selected a project, or passed.
        1. In the event of a tie in $ bid, the player with the highest total skill picks first.
            1. In the event of a tie in skill, the player with the 1st player marker goes first.
        1. Once a player passes, they may not pick a project again this round.
        1. After all players have picked a project, the player with the highest bid may pick a second project or pass, and so on until all projects have been chosen or all players have passed.
    1. When selecting a project, the Boss must be capable of fulfilling the project's setup cost from their total capacity - see example if unsure.

### Example round

Anna and Ben are Bosses. 

Anna has $15 and a total capacity of \[T\]\[T\]\[T\]\[T\]. However, Anna has ongoing projects costing $6/turn and \[T\]\[T\]\[T\], leaving her with $9 and \[T\] for this turn.

Ben has $7 and a total capacity of \[T\]\[T\]\[T\]\[T\]\[T\]\[T\]\[T\]. However, Ben has ongoing projects costing $5/turn and \[T\]\[T\]\[T\]\[T\]/turn, leaving him with $2 and \[T\]\[T\]\[T\] for this turn.

Anna has a completed project that gives her a bonus to R&D +3 and another completed project that gives her a bonus \[T\].

Ben has a completed project that gives him a bonus $2 and \[T\] for _Science_ projects.

At the start of the round, three workers are drawn:

#### Worker 1
Name: Boris\
Description: Call-centre operator
 - Costs
    - Time to train: \[T\]
    - $ per round to retain (salary) \[$\]\[$\]
 - Outputs
    - Productivity \[ \]\[ \]\[\*\]\[\*\]
    - Skill \[ \]\[ \]\[*\]\[\*\]
    - Leadership \[\*\]
    - Morale: :) :) :)

#### Worker 2
Name: Celia\
Description: Senior marketing consultant
 - Costs
    - Time to train: \[T\]\[T\]
    - $ per round to retain (salary): \[$\]\[$\]\[$\]
 - Outputs
    - Productivity \[ \]\[ \]\[ \]\[\*\]\[\*\]
    - Skill \[ \]\[ \]\[ \]\[\*\]
    - Leadership \[ \]\[ \]\[\*\]
    - Morale: :) :)

## CEO effects

1. When a worker becomes the CEO, the old CEO must retire, die or be fired:
    1. A CEO can retire if they have been in the company (at any position) for more than 10 turns.
        1. A retiring CEO costs the company $5 this turn, throwing a big retirement party.
    1. Whenever any project fails (see Projects), the incumbent CEO can be fired. However, if done, all remaining projects gain \[T\]\[T\] in delays.
    1. A CEO can die only through a random event. A new CEO should be chosen within 2 turns.
1. If conditions have not been met to retire, fire or kill off the CEO, the CEO remains.
1. CEOs cannot be demoted.
1. When resolving organisational structure:
    1. The CEOs leadership and skill bonuses are unlocked (if able).
    1. Earn $1 for each CEO productivity (NOTE: The CEO's productivity is not automatically unlocked, but can become unlocked through other effects).

Outsourcing (to the market)
Trade (with other players)
Player alliances?
