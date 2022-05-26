# quest-submissions

# Chapter 1 Day 1 Quest

# Explain what the Blockchain is in your own word.
A blockchain is a distributed database that is shared among the nodes of a computer network for recording transactions, tracking assets and building trust.

# Explain what a smart contract is.
A smart contract is a set of instructions that is deployed on the blockchain to act in a specific way.

# Explain the difference between a script and a transaction.
A script is used to view data on the blockchain and doesn't incur charges, while a transaction is used to change data on the blockchain and incurs charges.


# Chapter 1 Day 2
# What are the 5 Cadence Programming Language Pillars?
The 5 Cadence Programming Language Pillars are:
- Safety and Security
- Clarity
- Approachability
- Developers experience
- Resource Oriented Programming

# In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful?
- every smart contract must be safe and secure
- code should be easy to read 
- code should be familiar with other languages for easy transistion
- debugging should be easy and errors not had to trace for developers


# Chapter 2 Day 1
https://play.onflow.org/143229e9-47f7-4ccd-ab39-3d4aa5de2c8c?type=account&id=4f8af465-0553-4562-af27-609a0774eba9&storage=none
https://play.onflow.org/143229e9-47f7-4ccd-ab39-3d4aa5de2c8c?type=script&id=e3f351fd-4a55-4f9c-9ca6-b2fca1c6d5fc&storage=none

# Chapter 2 Day 2

# Explain why we wouldn't call changeGreeting in a script.
Recall that we can only read from and not modify a script, hence the reason why we we wouldn't call changeGreeting in a script.

# What does the AuthAccount mean in the prepare phase of the transaction?
It means that the smart contract is granting a particular account acccess to data in the account.

# What is the difference between the prepare phase and the execute phase in the transaction?
The difference is that the prepare phase gives access to data in the account, while the execution phase can't do that but can call functions or modify data in the blockchain.

# Pls find link below for question #4
https://play.onflow.org/0ef89793-f72b-45fc-b70a-bb4864d07d51?type=account&id=641f4181-2125-424c-91c5-149e95930a51&storage=none


# Chapter 2 Day 3

# In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.
https://play.onflow.org/d03d565a-b00b-46a2-a7b7-b68280de106a?type=script&id=fec6d96c-d754-40bd-abe9-e06cebe31ff1&storage=none

# In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!
https://play.onflow.org/d03d565a-b00b-46a2-a7b7-b68280de106a?type=script&id=fec6d96c-d754-40bd-abe9-e06cebe31ff1&storage=none

# Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).
The force unwrap operator unwraps an optional type without having to check if it's nil or not.
Example: https://play.onflow.org/d03d565a-b00b-46a2-a7b7-b68280de106a?type=script&id=fec6d96c-d754-40bd-abe9-e06cebe31ff1&storage=none

# Using this picture below, explain...
- What the error message means: It means it's an optional.
- Why we're getting this error: It is because String? is an optional so it maybe String or nil
- How to fix it: We canfix this by using the force unwrap operator (!).




