---
title: 用語集
taxonomy:
    category:
        - glossary
---

### 日本一充実したビットコイン用語集を作りたい！

[River Financial の Bitcoin Glossary](https://river.com/learn/terms/) をベースに、日本語のビットコイン用語集を構築中です。用語集作りに参加して、**ビットコイン**を稼ぎませんか？

以下の英語の用語説明を日本語にしてください。忠実な翻訳でなくて構いません。AI翻訳にかけて内容を理解した上で、ご自身の言葉で説明してください。

日本語の提案はGitHubでプルリクエストとして受付中。プルリクエストがマージされたら、報酬をライトニング⚡️送金します。<br>
提案手順は[こちら](https://github.com/lostinbitcoin/categories/wiki)の「2. 用語集の用語説明の提案手順」をご参照ください。

--
### ビットコイン用語集

### 索引 <a id="ta"></a>た

|  用語  |  英語表記  |  説明  |  報酬  |
| ---- | ---- | ---- |---- |
|<a id="durability"></a>耐久性| Durability |Durability is the ability of a good to retain its original state overtime. In order to be considered durable, a good must be difficult to damage or alter. Durability is a necessary property of money because the money must be able to sustain its value over time. For this reason, beans, shells, livestock, or other objects previously used as money did not succeed overtime because they were not durable. Likewise, gold emerged over other metals due to its durability: gold neither rusts, corrodes, or tarnishes.|2,100 sats|
|<a id="fungibility"></a>代替性| Fungibility |Fungibility is a property of goods which are interchangeable and indistinguishable. For example, pennies are all worth $0.01 and ownership of one penny is not preferable over any other penny. Fungibility is a desirable property for Bitcoin in order to maximize Bitcoin’s utility for individuals. If certain bitcoin are considered tainted, perhaps because of past ownership by criminals, those bitcoin could be deemed less valuable by regulated merchants or exchanges. Merchants could be required to check each bitcoin received to ensure they were not tainted. These restrictions would place immense burdens on consumers, merchants, and exchanges, discouraging adoption of Bitcoin. Privacy mechanisms such as CoinJoins attempt to ensure that bitcoin remains fungible in the future by providing a secure way of obscuring the past ownership of certain bitcoin, rendering the concept of taint unusable.|2,100 sats|
|<a id="timelock"></a>タイムロック| Timelock |A timelock allows a Bitcoin transaction to be created such that the recipient of the outputs cannot spend them for a specified time. The amount of time can be specified by either block height or Unix timestamp. The timelock is specified in a dedicated part of each transaction. However, most transactions simply leave the timelock blank to avoid using this functionality. Timelocks are useful for creating Hashed Timelock Contracts (HTLCs), which drive the Lightning Network.|2,100 sats|
|<a id="dust"></a>ダスト|Dust|If a piece of bitcoin, called a UTXO, is small enough, it may cost more in fees to spend it than it is worth. As fees rise, more and larger amounts of bitcoin may become dust. To avoid bitcoin turning into dust, it is a good practice to consolidate very small amounts of bitcoin into a single larger amount at a time when bitcoin fees are low.|2,100 sats|
|<a id="dust_attack"></a>ダスト攻撃|Dust Attack|Occasionally, attackers will send tiny fractions of bitcoin, around 500 sats, to random wallets. If the owner of the wallet does not notice, they may inadvertently include this piece of dust in their next transaction, leaking information about which bitcoin they own to the attacker. A dust attack is like placing a tracking device on a victim, allowing the attacker to view where the victim travels, or in this case, which bitcoin the victim owns. High quality wallets do their best to disallow users from including dust in their transactions in order to protect them from such attacks. If you notice tiny amounts of unsolicited bitcoin being sent to your wallet, you should not spend them as part of a transaction with other pieces of bitcoin. A dust attack only works if the victim spends the dust along with other UTXOs they own.|2,100 sats|
|<a id="taproot"></a>タップルート|  Taproot  |  Taproot is currently a proposed upgrade to Bitcoin which would introduce several new features. The Taproot upgrade is described in BIPs 340, 341, and 342, and introduces the Schnorr signature scheme, Taproot, and Tapscript. Together, these upgrades introduce new, more efficient, flexible, and private ways of transferring bitcoin.The Schnorr signature scheme is more efficient, secure, and quicker to verify than Bitcoin’s original digital signature scheme, ECDSA. Additionally, Schnorr signatures enable MuSig, a more efficient form of multisignature which would greatly increase the privacy and fee rate paid by multisig transactions.Taproot will enable sending to and spending from Schnorr public keys as well as enabling bitcoin to be sent to multiple scripts at once. In order to achieve this, a new type of ScriptPubKey called Pay-to-Taproot (P2TR) will be defined. The addresses for these scripts will use SegWit v1 and Bech32 encoding. | 2,100 sats|
|<a id="change_output"></a>チェンジ・アウトプット|Change Output|Bitcoin does not use accounts and balances. Instead, pieces of bitcoin, called UTXOs, are owned by individuals. These can be likened to physical bills in that when they are spent, they will usually require change to be given as their amount will almost never match the amount being paid. When a user creates a transaction, they select an input, a UTXO which they own, and create outputs. One output will go to the receiver’s address and the other output will be returned to the sender’s wallet, usually via a different address. The amount for this second output will be the change, which will amount to the sum of the inputs minus the amount spent in the first output and the transaction fee.|2,100 sats|
|<a id="chain_analysis"></a>チェーン分析|Chain Analysis|Chain analysis uses heuristics to analyse the blockchain and trace the ownership of bitcoin across transactions. Several companies exist solely to track and deanonymize individuals and their bitcoin using these heuristics. These companies sell their analysis to financial institutions and governments who are attempting to prevent fraud, money laundering, and other illegal activities. Chain analysis is a broad term, and should not be confused with the company called Chainalysis.|2,100 sats|
|<a id="anonymity"></a>匿名性|Anonymity|Anonymity is the quality of a person whose identity is unknown. An anonymous person uses a pseudonym to operate in public without revealing their identity. In the age of the Internet, anonymity is extremely hard to establish and maintain. Bank accounts, employers, social media, and telephone companies almost all require personal identification. The Bitcoin blockchain is inherently pseudonymous, not anonymous. Instead of a name, address, or phone number being linked to each transaction, only addresses, public keys, and signatures appear on the blockchain. These addresses do not themselves reveal who owns which bitcoin. However, using various heuristics and surveillance tools, governments and corporations can perform chain analysis to connect a users’s pseudonymous address to their real-world identity.|2,100 sats|
|<a id="transaction"></a>トランザクション|Transaction|トランザクションは、ビットコインの移動の記録として存在します。 
すべてのトランザクションは、ブロックチェーン上のブロックに記録されます。 
ほとんどのユーザーはビットコインのトランザクションを送信および受信するためにウォレットを使用します。 
ウォレットがバックグラウンドですべての技術的な作業を行うので、ユーザーは単にアドレスとそのアドレスに送信する金額を指定するだけです。
トランザクションの準備ができると、それはビットコインネットワーク上のノードにブロードキャストされます。
これらのノードはマイナーがブロックに追加するまでmempoolと呼ばれる保留中のトランザクションのプールにそのトランザクションを保持します。 
トランザクションがブロックに追加された時点で、そのトランザクションは確認されます。
トランザクションがブロックチェーンに少なくとも6ブロック保存されるまで待つのが安全な方法であり、最終的に決済されたと考えることができます。 
取引の仕組みは、インプット、アウトプット、署名の3つの部分から構成されています。
インプットとは支払者が使用することを選択したUTXOと呼ばれるビットコインの断片のことです。 
アウトプットとは指定されたアドレスに指定された量のビットコインを送り、新しいUTXO(未使用アウトプット)を作成することです。 
1つの取引にはいくつでもインプットとアウトプットを含めることができます。
最後にトランザクションを有効にするために、支払人はトランザクションに署名し、それによって彼らが使おうとしているインプットの所有権を証明する必要があります。
この署名は支払い者の秘密鍵を用いて作成さ れます。

トランザクションの例を見てみましょう。
アリスは1BTCのUTXOを所有し、ボブに0.4BTCを支払いたいと思っています。
そこで彼女は1BTCのUTXOを入力として使用します。
Bobに0.4BTCを送るために、アリスは2つのアウトプットを作成します。1つ目はBobに0.4BTC、2つ目は自分自身に0.59BTCの金額で送ります。 
つまり彼女は0.01BTCの取引手数料を支払ったことになります。
Key Fact: ビットコイン取引の手数料は、取引のアウトプットではありません。

手数料はアウトプットではありません。
インプットの合計 (1 BTC) からアウトプットの合計 (0.4 + 0.59 = 0.99 BTC) を引いたもので、マイナーによって徴収さ れます。
最後に、アリスは1BTCのUTXOを制御する秘密鍵を使って、ネットワークにブロードキャストする前に取引に署名します。
このトランザクションがブロックチェーンに追加されると、1 BTC UTXOは使用済みとなり、0.4 BTCと0.59 BTCの2つの新しいUTXOが作成され、それぞれボブとアリスに属することになります。|2,100 sats|
|<a id="txid"></a>トランザクションID（TXID）|Transaction ID (txid)|A txid or Transaction ID is a string of letters and numbers that identifies a specific transaction on the blockchain. The string is simply the double SHA-256 hash of a transaction. This hash can be used to look up a transaction on a node or block explorer. When signing a transaction, it is in fact the txid that is signed. Signing the txid ensures that if any part of the transaction changes, the transaction ID changes, and the signature is rendered invalid. Technically, a txid is not always a hash of the entire transaction. Since a signature cannot sign itself, signatures are not included in the txid, and thus signatures can be changed after their creation, sometimes without being invalidated. Before SegWit, this allowed a txid to change after the transaction was signed, a problem called transaction malleability.|2,100 sats|

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
