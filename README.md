# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Yusen Lin

_Student NetID_: yl162

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Stadium}
- Assumptions:
  - The football stadium can contain 10 thousand viewers. Since the university team is almost the best, the stadium is nearly full during a game. 80% of the audience are citizens and the remain are students in the university. There are plenty of parking pots around the stadium. The stadium has four main entrances. There are fifty areas in the stadium, each area owns a small store selling beverages and chips. The stadium is open-air.
  - There are three situations of a stadium. First is game situation. Second is training situation. Third is closing situation. For three situations, the plan of protection is different.

- Assets:
  - The safety of the audience. There is no doubt that the safety of human is the most important. Only in game situation. 
  - The order of the game. The game should be played in order, any factor disrupts the game should be scanned. Only in game situation.
  - The safety of athletes, referees, the cheerleading and any people related to the game. In game and training situations.
  - The integrity of all facilities in the stadium. We should also protect the property of the stadium. In all situations.
- Threats:
  - Terrorist attack. The stadium is full of people and it will be very dangerous if somebody shooting or bombing in the auditorium.
  - Extreme weather. Rain and storm can disrupt the order of the game. Fire can interrupt the game.
  - Stampede. When the game begins or ends, thousands of people swarm inside or outside the gate, it will be dangerous if somebody falls. 
  - Fighting between fans. The team is ranked high, which means it will face fierce games and fanatic guest fans. The hostility between fans cannot be ignored.
  - Throwing objects. Some fanatic audience may throw something to athletes or referees when they are extremely angry.
  - Theft. Thieves will never disappear. Wallets of the audience, assets in the store, cars parking outside the stadium…… everything can be targets of them.
- Countermeasures:
  - I will define three levels of the plan of countermeasures.
  - Level 1: When the stadium is closed.
  - All gates should be locked. There is one guard in front of each gate. Keep monitors around gates open and others shut off.
  - Level 2: When the team is doing daily training.
  - Open one gate only and is only accessible for approved people. Allocate a group of guards around the court to block non-related people including the media. Open all monitors in the stadium. 
  - Level 3: During the game.
  - Open all gates, each gate has enough fences to guide people in a line. For each gate, prepare two armed guards with a trained policed dog, two ticket checkers, and two security guards holding detectors to check any bags. Big baggage should be blocked outside the stadium.
  - Prepare about five areas for guest fans only. For each area, three should be one guider with loudspeaker and one guard. Around the court there should be more guards.
  - After the game, the audience should wait or leave according to the guider. During the game, if anything unusual happens, the guider should keep the order. There should be a group of armed guards patrolling in the stadium.


## Problem 2
- Scenario: {TSA}
- Assumptions:
  - All airports have enough money to purchase necessary equipment for safety checking. Tickets and identities of passengers have been checked before they reach the airport checkpoints. 
- Assets:
  - The safety of people in planes and airports. 
  - The safety of property of passengers and airports.
  - The efficiency of letting people go through checkpoints.
- Threats:
  - Hijackters. In 9.11, twenty hijackters passed checkpoints in four airports, that’s amazing. They may hide knifes in shoes, in umbrellas, in computers. They may hold plastic knifes, wood knifes (Sharp enough or looks sharp enough). They may carry some chemical materials to make bombs after checkpoints.   
  - Smugglers. Although most of smugglers avoid taking airplanes, but it is still possible. Smugglers, especially drug traffickers, may hide their drug in bottles, milk boxes and even stomachs.
  - The quality of security checkers. Security checking in airport is a boring and repeating job. A checker should face the hostility and sometimes even insult from passengers. How to make sure that a checker can work calm and efficiently is a problem.
- Countermeasures:
  - There should be three parts in checkpoints. First part is the lining part. Passengers can throw water bottles, lighters and anything forbidden by the rule to bins. Most of passengers are not bad guys, give them a chance to discard dangerous objects can increase efficiency. Several helpers are allocated to guide lining passengers to different checkpoints. Several police with police dogs should check whether there is drug in luggage. 
  - Second part is the scanning part. People should take off their shoes, their watches, their coats and glasses. Put them together with their electronic products. And let all these objects and their luggage be scanned by X-ray scanner. Two checkers should look at the screen and find questionable objects. The passengers will go through body scanner one by one to check whether they have metal objects. After that. There will be three body checkers per body scanner to make a body search. There is also one helper to guide passengers and transform baskets per scanner. 
  - The third part is the special checking part. Only passengers with questionable luggage should be took here and their luggage will be open and checked thoroughly. There should be at least four checkers in a special checking room and one checking room should oversee at most five scanners.
  - There should also be a group of police waiting for commands in case any passenger use force.
  - Checkers should be paid high and they should be qualified after at least six months special education. The airport should have power to cancel the ticket of any passenger who do not obey to checkers.


## Problem 3
- Scenario: As a lock designer, how to design a lock which supports face, fingerprint and password unlock for a house.
- Assumptions:
  - The lock is on the main door of a house. There are no other ways to break in the house, all windows are tightly closed and cannot be broke.
- Assets:
  - House owners can unlock easily while others cannot break in.
- Threats:
  - One holds a photo of the owner before his head to pretend to be the owner and break in.
  - One uses a special paper to get the owner’s fingerprint from the fingerprint scanner. He can copy the fingerprint and break in.
  - One uses a tiny monitor to watch the process that the owner types the password and break in.

- Countermeasures:
  - For the face detector, strong face recognition technology is necessary. Not only it should recognize the face, but also it should make sure that it’s a real face. A real face will vary and it has depth information, which tell it from a photo. The face detector should have a TOF camera and it should analyze one second to see if there are tiny change on the face. It doesn’t need to be strong enough to detect a face with occlusion or a shot from the side since it will decrease the accuracy of recognition.
  - For the fingerprint scanner, the technology is robust enough. But I want to add a brush to clean the scanner automatically after the door is open to prevent fingerprint stealers. 
  - The lock should have a cover on the number board so that people can type password secretly. I still need a brush to clean the board so that other cannot guess the password by observe the trace of typing.
  - The lock store information offline, it is a embedded system and will not connect to any other devices. People can only modify password/face/fingerprint information on the other hand of the lock, which is inside the house.


