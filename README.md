# ULSIM
Simulation of UL feasibility

## Backgroud
An insurance agent tried very hard to sell me a Universal Life insurance policy. The policy also provides *living benefits*, which allow you to borrow against the policy's cash value in the event of a critical illness. It sounds very enticing. Before purchasing the policy, I need to determine whether it is a good deal and understand the implications of using the living benefits.

## What is the Concern

The YRT (Yearly Renewable Term) type universal life insurance policy consists of a yearly renewable term life insurance and a tax-free investment account. Each year, the insurance charge is deducted from the premium first and then from the investment account value if needed. If the premium exceeds the charge, the remaining money is added to the investment account.

The idea is that after a certain number of premium payments at the beginning years, the investment account's annual return becomes large enough to cover the insurance charge and to increase account value. 

However, because the annual charge increases exponentially with age, the investment account value may eventually be insufficient to cover the annual charge. As a result, the policy could collapse.

To sustain the policy, one must pay extra premiums if the fund value falls below the annual charge. Since this typically occurs in the later years of the policy, the policyholder may be unable to afford the payment.

If the policy collapses while the policyholder is still alive, they will lose everything: no cash value and no death benefit. The policy is bad deal in such case. 

## Goal of the simulation
Out goal is to figure out the probability of the policy collapse at certain age. 

## SIM1.XMLS
Tab 
