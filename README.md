# WhaleHunt

**[How to play](#how-to-play) | [Example](#example-playthrough) | [Referrals](#how-can-i-receive-a-referral-fee) | [Refunds](#how-can-i-receive-a-refund-of-my-investment) | [FAQ](#faq)**

WhaleHunt is a game where you can take the money of the rich players by collaborating with the poor players.

## How to play

* Start a new game.
* Create a new pool.
* Invest in your pool.
* Convince other players to invest in your pool.
* Win if your pool is the largest at the end of the game.

See [example playthrough](#example-playthrough) for more details.

**Notes:**

* You will **receive 1% of all winnings** if you start a new game & invite other players (no need to win - [learn more](#how-can-i-receive-a-referral-fee)).
* You will **receive a refund** if somebody else invests in your pool (up to the sum of foreign investments - [learn more](#how-can-i-receive-a-refund)).

## Alternative strategy

Instead of creating a new pool, you can invest in somebody else's pool. This strategy works well if you have a small amount of capital. In this case, your playthrough will look like this:

* Join the game.
* Compare the pool sizes.
* Invest in the pool that will be the largest at the end of the game.

You can also speak with pool operators via in-game chat. This will allow you to evaluate the potential of the pool (some players will invest towards the end of the game). 

## Winnings distribution

* Sum the capital of all players.
* Subtract [refunds](#how-can-i-receive-a-refund-of-my-investment), [referrals](#how-can-i-receive-a-referral-fee), [fees](#what-is-the-game-fee).
* Split the remaining sum between investors of the winning pool (according to investor share).

See [example playthrough](#example-playthrough) to learn how much you can win.

### Player actions

* Start a new game:
  * Name
  * Currency (which token can be used as investment; you can choose any ERC20-compatible token)
  * Minimum capital (how much at least everybody needs to put into the game)
  * Maximum capital (how much at most everybody needs to put into the game)
  * Join before X (datetime before which new players need to join before)
  * Invest before Y (datetime before which existing players needs to invest; if the player doesn't invest, his money will go into his own pool; the game ends after this datetime)
* Join an existing game:
  * Your capital (how much you put into the game; must be greater or equal to "Minimum capital")
* Invest in a pool:
  * Your investment (how much you put into the pool; can be any amount, does not depend on "Minimum capital")
* Send a message to game chat.

## FAQ

### How can I receive a referral fee?

Start a new game to receive 1% of all winnings. 

* No need to win the game.
* No need to join the game (= no need to invest your money).

### How can I receive a refund of my investment?

Convince other players to invest in your pool. If you don't win, you will receive a refund up to the sum they invested in your pool. If you do win, you will receive a refund + winnings.

#### Example #1

* You invest 10 ETH in your pool.
* Bob invests 20 ETH in your pool.

You will receive a 10 ETH refund.

#### Example #2

* You invest 10 ETH in your pool.
* You invest 2 ETH in Alice's pool.
* Bob invest 5 ETH in your pool.

You will receive a 5 ETH refund (up to Bob's investment). 

### What currency can I use for playing?

You can use any ERC20-compatible token: WETH, WBTC, UNI, SUSHI, LINK, COMP, LEND...

Note: the currency is set by the creator of the game before it starts (every player uses the same currency).

### Can I invest in multiple pools?

Yes, you can diversify your investments between multiple pools.

For example: you can invest 30% in Alice's pool, 60% in Bob's pool, 10% in your pool.

### Can I invest 100% in my pool?

Yes, you can.

### Can I change my investment allocation?

No, each investment is final. Since other players also can't change their investment allocations, you can estimate the pool size without fearing that they will back out.

### What happens if I invest in somebody's pool, but he invests in my pool?

Your pool size is determined by the total invested amount. If you invest in somebody else's pool, then your investment is deducted from your pool & added to somebody else's pool.

Example:
* Alice invests 5 ETH in Bob.
* Bob invests 10 ETH in Alice.
* Alice's pool size becomes equal to 10 ETH.
* Bob's pool size becomes equal to 5 ETH.
* Alice wins.

### What is the game fee?

We charge 2.5% of winnings (after [refunds](#how-can-i-receive-a-refund-of-my-investment) and [referrals](#how-can-i-receive-a-referral-fee)).

## Example playthrough

* *Alice joins the game with 5 ETH*
* *Bob joins the game with 10 ETH*
* *Sam joins the game with 7 ETH*
* *Joe joins the game with 3 ETH*
* *Ted joins the game with 15 ETH*
* **Alice**: Hey guys, invest in my pool!
* **Bob**: Nah, I'll keep the money in my own pool.
* **Alice**: You'll lose it to Ted - he's got 15 ETH.
* **Ted**: Speaking of which... why don't you guys invest in my pool? You can't lose!
* *Ted invests 15 ETH into his own pool (total size: 15 ETH)*
* **Sam**: Listen guys, I have a plan. We can create a pool together and take out Ted and get all his money.
* **Alice**: Good idea. Bob, Joe - are you in?
* *Game ends in 5 minutes*
* **Alice**: Guys, you've gotta make a decision fast!
* **Bob**: I will wait until the last moment to decide.
* **Alice**: But if you wait too long, you'll lose anyway, because your money will go into your own pool (you only have 3 ETH)
* *Game ends in 3 minutes*
* **Sam**: Alright, we gotta move otherwise Ted wins. Alice, will you invest in me?
* **Alice**: Is this a proposal?
* **Sam**: Yes.
* **Alice**: I don't know... I need to think...
* **Sam**: Well, you've got 3 minutes to think.
* **Alice**: Why don't you invest in me? I also want a [refund](#how-can-i-receive-a-refund-of-my-investment).
* **Sam**: I've got 7 ETH, you've got 5 ETH, so it's fair that I receive the protection. Besides, you're already getting [referral fees](#how-can-i-receive-a-referral-fee) because you started the game.
* **Alice**: Alright
* *Alice invests 5 ETH in Sam's pool (total size: 12 ETH)*
* **Sam**: Come on guys!
* *Game ends in 1 minute*
* **Sam**: GUYS!!! 
* **Ted**: You should join me actually...
* **Bob**: I'm a rebel, Ted. I always wanted a revolution.
* **Ted**: Bob, if you join me, you'll win outright: we'll have 25 ETH total, they'll have 15 ETH total.
* **Bob**: I've never heard from Joe, maybe he is away. I'll get more if I join Alice & Sam. Sorry Ted!
* *Bob invests 10 ETH in Sam's pool (total size: 22 ETH)*
* *Game ends in 10 seconds*
* **Joe**: You left me no choice.
* **Bob**: OMG, he's back.
* *Joe invests in Sam's pool (total size: 25 ETH)*
* **Ted**: Noooo!
* *Game ends now*
* *Alice receives 8.12 ETH total = (5 ETH initial investment + 15 ETH winnings * (5 ETH share / 25 ETH pool)) * (1 - 0.01 referral fee - 0.025 game fee) + 0.4 ETH referral fee*
* *Bob receives 15.44 ETH total = (10 ETH initial investment + 15 ETH winnings * (10 ETH share / 25 ETH pool)) * (1 - 0.01 referral fee - 0.025 game fee)*
* *Sam receives 10.808 ETH total = (7 ETH initial investment + 15 ETH winnings * (7 ETH share / 25 ETH pool)) * (1 - 0.01 referral fee - 0.025 game fee)*
* *Joe receives 4.632 ETH total = (7 ETH initial investment + 15 ETH winnings * (7 ETH share / 25 ETH pool)) * (1 - 0.01 referral fee - 0.025 game fee)*
* *Ted receives 0 ETH*

## Strategies

## Design notes

* We need to prevent a situation where a single player can make an "obviously winning" decision. For example:
  * Alice joins the game with 5 ETH
  * Bob joins the game with 5 ETH
  * Sam joins the game with 5 ETH
  * ~ Alice can't invest in her pool, because Bob & Sam may collude against her. On the other hand, if she invests in herself, then she will create a Schelling point - other players need only 1 action to win by siding with her instead of 2 actions to win by colluding against her. A different situation ensues
* We need to prevent a situation where everybody invests in the same pool
  * Auto-win if at least one pool has >50% game size? 
