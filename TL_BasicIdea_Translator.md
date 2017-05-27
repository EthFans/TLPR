# TRUSTLINES NETWORK	
 
## Introduction 
* Hi. today i’m gonna present the basics of the Trustlines Network for you
* Hi。今天我将会向你展示Trustlines网络的基本情况。
* what is the Trustlines Network? 
* 什么是Trustlines网络？
* It’s a mobile payment app that extends on the original ripple idea but built on Ethereum
* 它是一个移动支付应用，延展了最初的瑞波（Ripple）概念，并建立在了以太坊平台上。
* And a decentralized platform for hosting customized and interconnected currency networks
* 同时也是一个用来维护定制化和内部链接货币的去中性化的平台
### ToC:
### 对C端用户： 
* In this video, I will give a brief motivation of why crypto currencies as we know them, are not a good medium of exchange for everyday payments
* 在这个视频中，我会简单介绍一下为什么数字货币并不是一个特别适合日常支付的交易中介
* Then, I’ll explain how the original ripple idea, can create a global payment network based upon the real world trust relationships, that exist between friends.
* 然后，我会解释最初的瑞波理念是怎么创造一个建立在现实世界信任关系（例如朋友之间）上的全球化支付网络
* Next, I’ll explain how payments facilitated in a chain of friends-of-friends allow for debt cancellation
* 接着，我会解释建立在朋友的朋友上的支付链条怎样使得债务抵消
* and finally, I’ll address the system's resistance against sybil attacks 
* 最终，我会阐述这个系统如何抵抗Sybil攻击。
## Adoption of cryptocurrency for payments
## 在支付中使用数字货币
* Many have seen blockchain as a promising solution to provide permissionless, decentralized, payments without central intermediaries
* 许多人将区块链视为一个令人放心的解决方案，可以提供无需许可、去中性化、不需要中央中介人的支付渠道。
* Unfortunately, that’s just not how it works today
* 不幸的是，目前它并不是这样运转的。
* Today, using cryptocurrency for payments comes with a poor user experience. 
* 当今，使用数字货币来进行支付往往带来很差的用户体验。
* Cryptocurrencies acquired to make payments, feel more like prepaid accounts or gift certificates than actual money.
* 被用来支付的数字货币，往往让人感觉更像使用一种预充值账户或是礼品卡，而不是在使用真的钱。
* This is because, They are usually bought with fiat first For example USD for Bitcoin
* 这是因为，这些数字货币往往是用法币购买获得的，例如用美金购买比特币。
  * Pay for them today, eventually use them later.
  * 先购买它们，最终在未来使用它们。
* Additionally, to make a payment, the average user needs to have:
* 额外的，为了成功支付，一个普通用户需要拥有：
  * A bank account
  * 一个银行帐号
  * An exchange account
  * 一个交易所账号
  * Some form of identification
  * 一些的身份证明
* These prerequisites render the technology inaccessible, and therefore useless for those, who’d need it the most> the unbanked Because they don’t have a bank account or proper ID in the first place: 
* 这些先决条件使得这个技术变得不容易被广泛使用，因此也使得最需要这个技术的人，即那些没有银行账户的人，反而不可能使用它。因为他们没有一个银行账户，也通常一开始就没有所需的身份证明：
* So we believe, broader adoption of cryptocurrencies, for payments, depend on a value proposition, that can outcompete existing centralized payment services, instead of relying on them.
* 所以我们相信，如果要将数字货币更广泛得用来支付的话，我们需要一种价值主张，即我们需要完全超越现有的中性化支付服务方式，而不是依赖于他们之上。
* We were looking for alternatives and then the original Ripple idea came up.
* 我们正在寻找其他选择时，最初的瑞波概念出现了。
 
## The Original Ripple Idea
## 最初的瑞波概念
* So what is the original ripple idea?
* 所以最初的瑞波概念是什么？
* Well, the foundation, is a network of people, who have existing trust relationships with each other. 
* 总得来说，整个网络的基石是人们的社交关系，那些已经存在的相互信任关系。
  * Credit lines, are established based on these mutual trust relationships
  * 信用额度是建立在那些共有的信任关系上的
  * For example, you would probably trust your mom, dad or one of your friends with a credit line of $10 
  * 例如，你应该会相信你的母亲、父亲或者你的朋友并给他们一个10美金的信用额度
  * On the other hand, you would probably not trust a “friend” who just added you on facebook with a credit line $10. Because that person is still a stranger to you 
  * 另一方面，你可能不会相信一个刚刚在facebook上加了你的"好友"并给他10美金的信用额度。因为这个人对你来说只是一个陌生人。 
* Next, let’s look at how trust relationships are used to establish what we call trustlines
* 接着，我们来看看这些信任关系如何被用来建立一个我们所谓的trustlines。
## A Trustline
## 一个Trustline
* A trustline exists, when two friends have give each other credit lines.
* 当两个朋友互相给对方赋予一个信用额度时，一个trustline就出现了。
* It means, that they allow their friend the opportunity, to borrow and pay with an amount, up, to a specified credit limit
* 这意味着，他们给予他们朋友一个机会来借用或者支付一定的金额，最高到他们所指定的信用额度限制。
* Here, we see Alice and Bob who have a trustline with each other
* 这里，我们看到Alice和Bob互相给予了trustline
* In this example, it means Alice has given Bob a credit line of $10
* 在这个例子中，这表示Alice已经给予了Bob 10美金的信用额度
* In return, Bob has also granted a credit line of $10 to Alice
* 相反的，Bob也给予了10美金的信用额度到Alice
### Balance
### 余额
* Suppose Alice needs to pay $5 to Bob
* 假设Alice需要支付5美金给Bob
* To make that payment, she spends 5$ of her $10 credit line with Bob 
* 为了完成支付，她花了Bob给予的10美金信用额度中的5美金。
* The current net balance of Alice and Bob’s trustline, is therefore that Alice owes $5 to Bob
* 目前Alice和Bob的trustline总余额因此是Alice欠Bob5美金。
* Alice can still spend $5,  Bob can now spend $15
* Alice现在还可以使用5美金，而Bob现在可以使用15美金。
 
### Payments between strangers
### 陌生人之间的支付
* Now let’s suppose Alice, needs to pay a stranger called, Charlie
* 现在我们假设Alice需要支付一个陌生人，Charlie
* They are not friends and do not know, or trust each other
* 他们不是朋友也不认识互相，更不相信对方。
 
### Payments between strangers II
### 陌生人之间的支付2
 
* Earlier, we saw Alice and Bob had a trustline which they used to pay each other with. But this trustline, can also be used to facilitate payments through trusted connections
* 之前，我们看到Alice和Bob已经有了一条用户互相支付的trustline。但是这个trustline也可以用来协助通过信用关系的支付
* If we can find a path of connected trustlines between Alice and Charlie, we can use these connections to make a payment
* 如果我们能找到一条在Alice和Charlie之间trustlines的链接通道，那么我们就可以用这些链接来完成支付。
 
 
### Payments between strangers III:
### 陌生人之间的支付3
* The path that is used for the payment must also have sufficient capacity.
* 这条用来完成支付的通道也必须有足够的支付能力。
* Capacity means that the trustlines must be equal to or larger than the amount we want to send
* 支付能力在这里指的是trustlines必须等于或者大于我们希望发送的金额
* Once we find a path with sufficient capacity, we can make a payment. 
* 一旦我们找到了一条拥有足够支付能力的通道，那么我们就可以完成支付。
 
 
### Payments between strangers IV
### 陌生人之间的支付4
* So we see there is a path with sufficient capacity through Bob
* 所以我们看到了一条通过Bob拥有足够支付能力的通道
* To make a payment, Alice spends $5 of her $10 credit line, that she has with Bob, and Bob spends  $5 of his $10 with Charlie
* 为了完成支付，Alice使用了她与Bob 10美金信用额度中的5美金，然后Bob使用了他与Charlie 10美金信用额度中的5美金
* What is cool about this feature is that Alice paid someone she does not know or trust,
* 这里面最酷的一点是，Alice支付了一个她完全不认识或者说不信任的一个人，
* Bob’s net balance remains unchanged because he spent and made the same amount
* Bob的总余额保持不变，因为他花费的数额和获得的数额一样

* And Charlie got paid with money he can trust from somebody that he knows.
* 同时，Charlie会被他认识而且信任的人支付。
* In fact, no one owes, or has money from somebody that they do not know or personally trust.
* 实际上，没有人将会结欠他不认识或者不相信的人任何金额。
* Not before or after the payment. 
* 支付之前之后都不会发生。
* This also scales out, if we put several people between Alice and Charlie, everyone would only be indebted to someone they have trusted with a credit line
* 当这个规模化后，如果我们将很多人放在Alice和Charlie之间，所有人都仅会与他们给予过信用额度的人发生借贷关系。
 
### Debt cancellation
### 债务抵消
* You may be thinking that this sounds kind of impractical.
* 你也许会觉得这个点子听起来好像不太实际。
* Because now, you would have to run around and collect money all day 
* 因为现在好像你必须一天都跑来跑去才能收回欠款
* But that is actually not necessary
* 但其实不需要这样做
* And this is a quite powerful feature of the setup: we can mostly avoid settling
* 这其实是整个系统中很强大的一个功能：我们基本上可以避免结算
* Let’s add Dave into the picture 
* 让我们把Dave加入这个场景
* He wants to pay Bob $5
* 他希望支付Bob 5美金 
* When many users are on the same network, the flow of money will naturally go in many directions
* 当许多用户都基于同一个网络的时候，资金将会自然得流往许多方向
* This will create a circular flow of money
* 这将会造成一种资金的循环流动
 
### Debt Cancellation II
### 债务抵消2
* Meaning Debt cancels out over time
* 这意味着债务将会随着时间互相抵消
* And so real world settlements are in most scenarios unnecessary
* 这也是为什么现实世界中的结算在许多情况下不再必要
 
 
### Closing a trustline
### 关闭一条trustline
* So sometimes relationships change - Alice and Bob have a fight and they don’t like each other anymore
* 所以有的时候人际关系会发生变化 -- Alice和Bob吵了一架并且他们不再互相交流
* The problem is, that Bob owes Alice money 
* 但问题是，Bob欠Alice钱
* And since Alice doesn’t trust Bob she wants to close the credit line,
* 因为Alice不再相信Bob所以她希望关闭这个信用额度，
* But, she doesn’t want to go and ask Bob to settle so they can close it.
* 但是他不希望去找Bob来结算从而关闭这条线。
 
### Closing a trustline II
### 关闭一条trustline 2
* Alice can instead pay herself with the money Bob owes her
* Alice其实可以支付自己Bob所欠她的金额
* In doing so, the payment runs through a different path which reduces her trustline with Bob to zero
* 这样做之后，这笔钱会通过许多条不同的通道来降低她与Bob之间的trustline并最终归零
* The payment she makes  changes the individual trustlines so that Bob is indebted to Ed, who is indebted to Alice
* 这笔支付交易会改变个人trustlines以至于Bob会欠Ed的钱，而Ed会欠Alice的钱
* the net balance of the involved parties accounts, do not change. 
* 但是所有相关方账户的总余额将保持不变。
## Sybil Attack
## Sybil 攻击
* The purpose of a sybil attack, is to attack a network by creating multiple, fake, accounts
* Sybil攻击是通过创造多个虚假账户来攻击一个网络
* Sybil attacks are something all social networks are exposed to 
* Sybil 攻击是所有社交网络都会面临的问题
  * For example: by creating fake accounts on facebook that befriends real people to steal their data
  * 举个例子：通过在facebook上制造虚假账号并与真实账户成为朋友从而偷去他们的数据
* So here’s an evil idea by Eve:
* 所以这里的Eve有一个邪恶的想法：
  * Why not just cheat the system? 
  * 为什么不尝试欺骗整个系统？
* Eve could just create many fake accounts by using a proxy server, and give herself millions, within the system 
* Eve可以通过代理服务器来创建多个虚假账户，并且给她自己在系统里授信一百万美金
* Eve thinks she can get away with this once the fake money has been traded into the network
* Eve认为一旦假钱能被交易进入整个网络，她就可以成功欺骗系统
* In other words, Eve believes any debt created on the platform is fungible, regardless of the trustlines used: 
* 换句话说，Eve相信这个平台上的任何债务都是可以相互替代的，不论使用了哪几条trustlines：
* This would be similar to FIAT currency, where a perfectly made fake dollar is indistinguishable from a real dollar to normal users
* 这将会类似于法币，在法币系统中一张完美的假钞对于一般用户来说与一张真钞是一样且不可分辨的
## Sybil Attack II
## Sybil 攻击2
* However, in the trustlines network, she is unable to do that
* 然而，在trustlines网络中，她是无法这样做的
* Even though Eve supposedly has millions of dollars in her trustlines, she cannot spend them in the network
* 虽然Eve的trustlines理论上拥有百万美金，但是她无法在整个网络中使用它们
* While Eve has real friends who trust her, they do not trust her fake accounts.
* 当Eve拥有现实中的朋友相信她时，他们不会同时相信她的假账户。
* She therefore needs to send money through her real account and cheat her friends
* 她因此需要从她的真实账户发送钱并欺骗她的朋友
* But even though she can do that. She cannot send the large sums of money
* 但是即使她能做到这点，她并不能发送如此巨大数额的钱
* Eve’s friends have not given her a credit line of  $ 1 million and won’t, because they do not trust her with that amount of money
* Eve的朋友并没有给予她百万美金的信用额度也不会这样做，因为她们不可能相信她到能给予如此大的额度
* In other words: Eve does not have a sufficient capacity to spend her money with her friends.
* 换句话说： Eve不会拥有足够的支付能力来在她的朋友网络中花这些钱。
* Additionally, Eve’s fake accounts need to send money through Eve’s main account because:
* 额外的，Eve的虚假账号一定要通过Eve的主账号才能发送钱，因为：
  * Valuable trustlines are backed by real world identities
  * 有价值的trustlines需要现实世界中的真实身份来支持
 
 
## And that’s the original idea
## 这是最原始的概念
* If you are curious to see applied examples of the original ripple idea we can recommend looking up Hawala banking or correspondence banking
* 如果你有兴趣了解这些应用了原始瑞波理念的案例，我们推荐可以研究一下Hawala银行系统或者相关的银行系统。
* The basic idea is:
* 基本的概念如下：
  * Credit lines with people you trust, varying by how much you trust them
  * 给予你信任的人额度，并且根据信任程度不同调整
  * People you trust anywhere in the real world, for example your friends or family
  * 你信任的人们可以在现实世界中的任意地方，例如你的朋友或者家人
  * You can send money through trusted connections 
  * 你可以通过信任的链接发送钱
  * And pay anyone in the network
  * 你可以向任意网络中的人进行支付
  * You can close a trustline, if your balance with the other person is zero.
  * 只要你和某人的余额为0，你就可以关闭这条trustline
  * And because trustlines are linked to real world identities, sybil attacks do not work.
  * 因为trustlines是与现实世界身份链接的，sybil攻击不会生效
  * Thank you for watching
  * 谢谢观看
