- candidate list for election
  - Jemar himself
  - someone for the worker's "party" 
    - Whoever this is will be backed by the shattered cult, should lead to some fun dilemmas for the party. They won't directly take over the town because that's not their goal
    - Manny Barkeep? Would be a reasonable choice as he's smart and knows how to deal with people in power well, but is still very much one of the working class. Also is an NPC the party already likes
  - someone for the adventurer's "party"
    - Maybe the knight they met and made fun of in the posh bar?
    - Bari?
  - someone for the aristocracy's "party"
    - probably invent a new NPC
    - Daerlin the depressed artist? that would at least be fun

- gonna give the party a list of how all the NPC's they've met are currently leaning, in terms of #1 ranked vote at least

- "plot hook" for the session - at the announcement of the candidates, once the worker's party candidate is read off, some noble will yell out in protest saying that the new mayor shouldn't be a commoner, to which several other rich assholes and a few adventurers will agree, saying they won't abide by this election if the candidates aren't all "who this town is for," which is to say adventurers
  - I want to lead into that strike/strike-breaker conflict, this might be the best way to do that at this point


### Rough timeline for what I intend to happen - who knows what the party will do:
- session opens on the party back from walking trip
- gently suggest they hang out in the various taverns since everyone will be talking about the election, get their fingers on the pulse
  - Could have Daerlin sit down at their table and announce (to them) their intent to run, they'll be very excited and talk about how they thinks they could turn this place into the artistic hub of this world or something
  - Could run into the 3 candidates where each of them "least belongs," in a sense: meet the worker's party candidate in the upper class bar where he works, meet the aristocratic candidate in the adventurer bar where they're trying to fit in with people they aren't, meet the adventurer candidate out in the streets, not a weapon or piece of armor in sight
  - in general stumbling across the 3 candidates sounds like a solid plan, hint at it a bit so they catch on to the fact that they'll be the candidates so they think there won't be any surprises at the nomination reading the following noon
- Next day the candidates are announced by the bishop at noon
  - Manny Barkeep's name will be read second-to-last, and there will be an outcry of protest by some adventurers/nobles. They will be a noticeable minority (for the moment at least)
  - Jemar's name is read off last, "and finally, having received the most nominations of all candidates for whatever that's worth, we have the incumbent and current mayor, Jemar"
    - Obviously will be a surprise to the party
- After the nomination reading there will be a lot of talk, both about whether the working class should have a candidate and about where the hell Jemar is
  - I'm kind of betting on the party bringing something up about "wait how is he nominated, did he submit it himself?", and that leading to some tension
- People will start talking about how they haven't seen Jemar in a couple days, and that someone should go check on him, maybe he's sick
  - will the party have a way to keep this from happening??? Idk
- If the NPCs do end up checking on Jemar, they'll find him dead in his living room, seemingly having died from choking on his food, with the basement being sealed off
  - This will have been Achiel manipulating events via a surrogate: moving Jemar into the main part of the house, moving Chei back into the hidden part of the house and wiping the memories of Chei, Bill, Zatari and Jeeves about how this happened, but they will notice the hole in their memory
  - Maybe Jemar isn't actually dead, Achiel just made it look like he is, and he'll wake up after the election? that could be fun
  - there will be no suspiscion on the party unless they massively fuck something up, as they'll have an alibi of hundreds of people having seen them at the nomination reading
  - Presumably the crowd will leave and the party will find an excuse to stay behind and figure out what the fuck happened
    - Ormen will stay behind as well to tell the party that during the nomination reading he felt extreme magical power, but couldn't investigate it at the time. Rather, not magical strength directly, but extreme precision that speaks of extreme power
    - hopefully they clue in that this is probably the guy from their dream
    - If they talk to bill and Chei (and Zatari and Jeeves if they question them), they'll say that all of a sudden they found themselves in a different place than before and Jemar was missing. By the time they talked to each other and figured out they had the same hole in their memory, they heard people coming and sealed off the hidden part of the house again
- The crowd will take Jemar's body off for inspection, and start throwing suspiscion at every corner
  - the narrative that will prevail, since what started this conversation about an election is that people have a problem with the mayor, is that the working class killed him and lied to the party to do the whole election thing
  - Between this theory and the already-existing animosity towards the working class having a candidate, later that evening there will be a large protest of adventurers and nobles, protesting the working class candidate and threatening to boycott the election/not follow it's results
  - Partially because of the shattered cult egging people on, there will be a counter-protest by the miners/farmers/servants/barstaff/etc. fighting for their right to have representation and saying they'll strike and the city will fall to pieces if their candidate isn't recognized
  - at some point this will escalate to violence and we'll finally have a combat encounter again
  - Said combat encounter will eventually be resolved by Ormen stepping in and using his skills to turn the tide for the workers?
    - metaphor for how he's planning to throw the election in their favour anyways

All this should lay some fun tension for the actuall debate/election


What actually happened
- party gets back from walking Trip, spends some time chatting with people around town including Daerlin and Manny Barkeep, then sleeps
  - Ran into Siril who was talking to people in the working class bar, which the party found concerning
- In the morning we fast-forward to the reading of the candidate's names
  - Party unnerved by the dissent from the crown when manny Barkeep's name is read off
  - Party very concerned when jemar is named as a nominee
- Party spends some time interviewing each of the 3 candidates to see what they're about:
  - Manny Barkeep: The working class candidate, very much wants to immediately reform the town if he's elected, at least once he can hire the right people to help him. The party told him more or less the full spiel about the monster town, he's cool with it and wants to carefully find a solution
  - Bari: Very much a status-quo candidate; interested primarily in keeping adventurers happy and the loot properly divided up. Wants to abolish the lift debt but otherwise keep things the same
  - Daerlin: Interested in the long-term future of the town after the monsters and treasure dry up. Has grand plans about turning the town into a hub of arts and culture in the future. Mostly thinks that things are running okay as they are, minus the 10k lift debt thing. When prompted about worker's conditions, they said some vague stuff about an audit, but didn't seem to think there was much of an issue







$workerHp=550
$adventurerHp=432


def workerDMG(n)
  $workerHp -= n
  $numWorkers = ($workerHp.to_f / 11.0).ceil
  puts "#{$numWorkers} workers remaining"
end


def adventurerDMG(n)
  $adventurerHp -= n
  $numAdventurers = ($adventurerHp.to_f / 18.0).ceil
  puts "#{$numAdventurers} adventurers remaining"
end
