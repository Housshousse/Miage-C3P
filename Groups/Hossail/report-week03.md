# Rapport de la troisième semaine

### Mohammad Hossein ESLAHI

### Souhail OUARGUI

Here is what I learned from the Objects State and Behavior Course this week:
**1) Objects vs Data:**
I learned that objects are more than just a data structure. They are about behavior and they should encapsulate logic so the clients can reuse that logic without duplicating it.

**2) Fat classes are bad:**
I learned that we have to avoid big classes that use a lot of conditional code to check types. It is better to favor dispatch by using a class hierarchy to encapsulate knowledge, and we should apply the "Do not ask, tell" principle.

**3) Global variables and Singleton:**
I learned that global variables make code very difficult to test, so we should avoid them and think modular. I learned also that the Singleton pattern is highly misunderstood. We should only use it if we really need to ensure there is only one instance available at a time, not just because it makes it easier to access.

**4) Decorator:**
I learned that decorators let us dynamically attach additional responsibilities to an object. It is a good alternative to subclassing.

**5) Methods and Blocks:**
I learned that executing a method is the elementary unit of reuse. I learned also that Blocks (closures) help build powerful APIs by encapsulating logic and actions, like making sure things initialize and terminate.

And for this week I also added some other tests to the chess game after understanding its components.

##### What I struggled with:

for The chess game I struggled a little bit at first to understand the game core classes and components, then when I went ahead to the first test, when I finished it i managed to understand more.
