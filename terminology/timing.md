---
title: Timing
description: Definitions of timing related terms
---

# Timing

- :exclamation: A **tick** is defined as computing and updating to the next logic state. This means a tick is a transition, not a state. Here are some examples
  - "During the next tick, the logic gate will turn on"
  - "After the next tick the logic gate will be on"
- :exclamation: **Delay** is the amount of ticks needed for a signal to go from the first determined input gate to the last determined output gate.
  - For the purpose of this determined means that you cannot change the gate type to any other type without breaking the logic
- :exclamation: **Throughput** is the ratio of the amount of inputs that can be taken or outputs that can be calculated each amount of ticks.
  - Example: If you can only have 2 input every 5 ticks (say you have an adder, and the A and B inputs are given through the same bus) this input throughput is 2/5=40%.
  - Most of the time your component only takes one input per each amount of ticks. So if it can take 1 input every 5 ticks (That same adder, but with separate input buses for A and B, where you give the two numbers at the same time), the input throughput is 20%.
  - :bearing: **Full throughput** means it can accept a new input/output every tick. (you would say "the input is full throughput")
- :bearing: **Concurrent** means the inputs/outputs arrive at the same time.
- :bearing: **Fixed delay** means that the time it takes for an input to produce an output does not depend on the input.
- :bearing: **Balanced** means that a component is full throughput at the in and output, concurrent at the in and output, and fixed delay. This also means that if the logic circuit were to be converted to a directional graph, that the distance from each input to the output is the same, and that all the different paths from a gate to any output gate have the same length.
