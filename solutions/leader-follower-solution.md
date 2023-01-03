Solution:

looks like a consensus problem, I will describe a solution of mine with N < 10, since the pourer has already marked 1st and last positions, because if the analyzing speed of all the guests are same then every one will compete for the positions marked as 1st and last leading into a chaos. So, if every guests comes into a conclusion as who will be their leader(considering that the leader is the one to distribute water equally to all guests, so that nobody is thirsty) to place the cup in position marked as 1st and the final follower who is willing to merge with leader to create a proper distribution amongst all the guest then we have a solution of having a multi node setup with equal proportion of data in each nodes (considering the cups as nodes).

There is one more situation as the problem says, the guests are smart and can cheat, so in this case, if we consider the levels of smartness are different then the leader is the one who convinces others to become his follower and appoints a final follower according to his choice. And eventually the leader drinks the water from the cup and doesn't share and so does the final follower appointed by the leader.

If the levels of smartness are same, then their is an unavoidable race condition, which can only be solved by the pourer

Assumption taken - Here the level of smartness is equivalent to the ability to convince

The leader election problem:

The leader can be elected with a incentive based system; There is condition where each guest who wants to be a leader puts down something valuable from their end and the one who puts down the most valuable item will get to be the leader (this is a fair and square deal). There is no cheating here and this builds a trust based system  for the election of the leader

The last follower selection problem:

This will happen when the leader gets elected and he randomly wants to conduct a race amongst other guests, who ever has his/her hands first to the valuable item gets to be his last follower.


Cheat condition:

There is a high probability that the leader and follower will definitely cheat, but considering the fact that its already water crisis and they have spent a long time electing leader and follower. They can even form an organized way of getting more water from different places with less time to spend because they already have created a trust based system.

The dishonest follower:

If the follower acts dishonestly and refuses to recognize him as a leader, then he eventually looses any chance to become a leader or a follower further. Then voting system will take its effect if such a scenario occurs. But technically speaking, one who holds the asset, will definitely recognize the leader and vote for him because its always a win-win situation for him