# How to troll a GM for fun and profit

## TL;DR
I believe it is possible to set up an in-game business offering NPCs a messaging service with end to end encryption.

## Preface

A little while ago while playing pathfinder, a sequence of events occurred in-game which gave me an idea.

It was the first time running a game for our GM, so occasionally the rules were a little scrappy, and every now and then they let us do something which _perhaps_ a more experienced GM would've avoided.

We were given two things which I believe allows us to do some really interesting things.

>Disclaimer: Our GM is great and we are having a lot of fun in our game, this is just a thought exercise to see how far we can break the rules we were given.

## The two things

##### 1. Early game doggos
In one of our first few sessions the party was attacked by dogs, pretty standard stuff. However, myself and another player decided that we wanted to capture the dogs, and keep them as pets.

We managed to engage the dogs in a grapple and somehow kept succeeding on our grapple checks for the rest of the fight and then continually while doing other things for the rest of the session. Eventually the GM, bored by our persistence, decided we could keep the dogs as pets.

##### 2. Magical sausages
A little while later we were fighting some giant bats in a crypt, I landed a dual wielding double crit and sliced a bat into a thousand tiny pieces. The GM decided that as a reward for mincing the bat we could turn it into a sausage (the GM named it 'batwurst') which they assured us would surely have interesting magical properties.

As it turns out, a batwurst sausage, when put in a cast iron pan for 10 minutes, duplicates and turns into two batwurst. In order to balance this, batwurst go rancid after two days (apparently they smell worse than anything) and so each individual sausage has a limited life span.

## Hypothesis

With pet dogs and magical doubling sausages I believe it is possible to set up an in-game business which offers NPCs a secure messaging service with end to end encryption utilising Diffie-Hellman key exchange.

## Background

So, encryption. What are? Why for? How do?

Encryption is a tool we use when communicating, at it's core it allows us to determine who is able to read a message and who isn't. There are some obvious applications for encryption like protecting credit card details when making purchases online, but it's also a great idea to use it for everyday communication. With access to sophisticated encryption algorithms and powerful smartphones many messaging applications offer us end to end encryption.

Now in the world of pathfinder we won't have access to powerful computers, in fact we will have a complete lack of even moderate computational power. As such encrypting everyday communications between thousands of NPCs is probably not going to work, so instead we'll be focusing on encrypting infrequent and highly sensitive messages between powerful and/or wealthy characters. I think it's pretty reasonable to assume that there are some people who would jump at the chance to have their communications sent with the knowledge that only their intended recipient will be able to read them.

As for how encryption works, at it's most basic level you have a message known as the `plaintext` and an algorithm to encrypt it called the `cipher`. You apply the cipher to the plaintext to create the encrypted message called the `ciphertext`, you send the ciphertext to your recipient and they use another algorithm to decrypt it back into the plaintext. In order to stop anyone else from decrypting the ciphertext the cipher uses a secret `key` which the sender knows, the algorithm to decrypt the message requires the same key to work, essentially the sender and reciever have a shared secret which allows them to securely send messages to each other.

## Key exchange

## Doubling

## Mersenne primes

## Dog tricks

## Hashing

## Implementing division

## Implementing modulo
