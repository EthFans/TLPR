# TRUSTLINES NETWORK	
 
## Introduction 
* Hi. today i’m gonna present the basics of the Trustlines Network for you
* what is the Trustlines Network? 
* It’s a mobile payment app that extends on the original ripple idea but built on Ethereum
* And a decentralized platform for hosting customized and interconnected currency networks
### ToC:
 
* In this video, I will give a brief motivation of why crypto currencies as we know them, are not a good medium of exchange for everyday payments
* Then, I’ll explain how the original ripple idea, can create a global payment network based upon the real world trust relationships, that exist between friends.
* Next, I’ll explain how payments facilitated in a chain of friends-of-friends allow for debt cancellation
* and finally, I’ll address the system's resistance against sybil attacks 
 
## Adoption of cryptocurrency for payments
* Many have seen blockchain as a promising solution to provide permissionless, decentralized, payments without central intermediaries
* Unfortunately, that’s just not how it works today
* Today, using cryptocurrency for payments comes with a poor user experience. ‘
* Cryptocurrencies acquired to make payments, feel more like prepaid accounts or gift certificates than actual money. 
* This is because, They are usually bought with fiat first For example USD for Bitcoin
  * Pay for them today, eventually use them later.
* Additionally, to make a payment, the average user needs to have:
  * A bank account
  * An exchange account
  * Some form of identification
* These prerequisites render the technology inaccessible, and therefore useless for those, who’d need it the most> the unbanked Because they don’t have a bank account or proper ID in the first place: 
* So we believe, broader adoption of cryptocurrencies, for payments, depend on a value proposition, that can outcompete existing centralized payment services, instead of relying on them.
* We were looking for alternatives and then the original Ripple idea came up.
 
## The Original Ripple Idea
* So what is the original ripple idea?
* Well, the foundation, is a network of people, who have existing trust relationships with each other. 
  * Credit lines, are established based on these mutual trust relationships
  * For example, you would probably trust your mom, dad or one of your friends with a credit line of $10 
  * On the other hand, you would probably not trust a “friend” who just added you on facebook with a credit line $10. Because that person is still a stranger to you  
* Next, let’s look at how trust relationships are used to establish what we call trustlines
## A Trustline
* A trustline exists, when two friends have give each other credit lines.
* It means, that they allow their friend the opportunity, to borrow and pay with an amount, up, to a specified credit limit
* Here, we see Alice and Bob who have a trustline with each other
* In this example, it means Alice has given Bob a credit line of $10
* In return, Bob has also granted a credit line of $10 to Alice
### Balance
* Suppose Alice needs to pay $5 to Bob
* To make that payment, she spends 5$ of her $10 credit line with Bob 
* The current net balance of Alice and Bob’s trustline, is therefore that Alice owes $5 to Bob
* Alice can still spend $5,  Bob can now spend $15
 
### Payments between strangers
* Now let’s suppose Alice, needs to pay a stranger called, Charlie
* They are not friends and do not know, or trust each other
 
### Payments between strangers II
 
* Earlier, we saw Alice and Bob had a trustline which they used to pay each other with. But this trustline, can also be used to facilitate payments through trusted connections
* If we can find a path of connected trustlines between Alice and Charlie, we can use these connections to make a payment
 
 
### Payments between strangers III:
* The path that is used for the payment must also have sufficient capacity.
* Capacity means that the trustlines must be equal to or larger than the amount we want to send
* Once we find a path with sufficient capacity, we can make a payment. 
 
 
### Payments between strangers IV
* So we see there is a path with sufficient capacity through Bob
* To make a payment, Alice spends $5 of her $10 credit line, that she has with Bob, and Bob spends  $5 of his $10 with Charlie
* What is cool about this feature is that Alice paid someone she does not know or trust,
* Bob’s net balance remains unchanged because he spent and made the same amount
 
* And Charlie got paid with money he can trust from somebody that he knows. 
* In fact, no one owes, or has money from somebody that they do not know or personally trust.
* Not before or after the payment. 
* This also scales out, if we put several people between Alice and Charlie, everyone would only be indebted to someone they have trusted with a credit line
 
### Debt cancellation
* You may be thinking that this sounds kind of impractical.
* Because now, you would have to run around and collect money all day 
* But that is actually not necessary
* And this is a quite powerful feature of the setup: we can mostly avoid settling
* Let’s add Dave into the picture 
* He wants to pay Bob $5 
* When many users are on the same network, the flow of money will naturally go in many directions
* This will create a circular flow of money
 
### Debt Cancellation II
* Meaning Debt cancels out over time
* And so real world settlements are in most scenarios unnecessary
 
 
### Closing a trustline
* So sometimes relationships change - Alice and Bob have a fight and they don’t like each other anymore
* The problem is, that Bob owes Alice money 
* And since Alice doesn’t trust Bob she wants to close the credit line,
* But, she doesn’t want to go and ask Bob to settle so they can close it.
 
### Closing a trustline II
* Alice can instead pay herself with the money Bob owes her
* In doing so, the payment runs through a different path which reduces her trustline with Bob to zero
* The payment she makes  changes the individual trustlines so that Bob is indebted to Ed, who is indebted to Alice
* the net balance of the involved parties accounts, do not change. 
## Sybil Attack
* The purpose of a sybil attack, is to attack a network by creating multiple, fake, accounts
* Sybil attacks are something all social networks are exposed to 
  * For example: by creating fake accounts on facebook that befriends real people to steal their data
* So here’s an evil idea by Eve:
  * Why not just cheat the system? 
* Eve could just create many fake accounts by using a proxy server, and give herself millions, within the system 
* Eve thinks she can get away with this once the fake money has been traded into the network
* In other words, Eve believes any debt created on the platform is fungible, regardless of the trustlines used: 
* This would be similar to FIAT currency, where a perfectly made fake dollar is indistinguishable from a real dollar to normal users
## Sybil Attack II
* However, in the trustlines network, she is unable to do that
* Even though Eve supposedly has millions of dollars in her trustlines, she cannot spend them in the network
* While Eve has real friends who trust her, they do not trust her fake accounts. 
* She therefore needs to send money through her real account and cheat her friends
* But even though she can do that. She cannot send the large sums of money
* Eve’s friends have not given her a credit line of  $ 1 million and won’t, because they do not trust her with that amount of money
* In other words: Eve does not have a sufficient capacity to spend her money with her friends.
* Additionally, Eve’s fake accounts need to send money through Eve’s main account because:
  * Valuable trustlines are backed by real world identities
 
 
## And that’s the original idea
* If you are curious to see applied examples of the original ripple idea we can recommend looking up Hawala banking or correspondence banking
* The basic idea is:
  * Credit lines with people you trust, varying by how much you trust them
  * People you trust anywhere in the real world, for example your friends or family
  * You can send money through trusted connections 
  * And pay anyone in the network
  * You can close a trustline, if your balance with the other person is zero.
  * And because trustlines are linked to real world identities, sybil attacks do not work.
  * Thank you for watching
