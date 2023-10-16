# Memcached challenge

[Memcached](https://memcached.org/about) is a in-memory key-value store.

The idea of this challenge is to measure if a developer is able to familiarize himself/herself with a new codebase and extend it with new functionalities.
This is particularly interesting because it is a real-world experience that a developer will need to suceed in a new job.

memcached is a key-value store. That means we can tell it to remember something (an association between a key and a value), and then later ask for that key again, and it’ll tell us the value it remembered.

## The Challegne

The idea here is to implement a new command that works similarly to the `incr` command, that can be used to increment an intenger with another integer N.
The new command is the `mult` command. It can be used to multiply an integer by another integer N.

## Credits and Better Description

This challenge was orignally brought Arthur O'Dwyer on [this post](https://quuxplusone.github.io/blog/2022/01/06/memcached-interview/#memcached-is-a-key-value-store.).
You can also see a better description and context of the problem there.
