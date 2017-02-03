# rlcourse-january20-bengioe

Actually january 27.

I tried implementing recognizers to do off policy montecarlo but failed. I'll try harder over the week end.

The thing I learned is that off-policy creates much more variance than on-policy, which is expected but also vividly felt experimentally, even in very simple MDPs.

My python notebook creates a 4 state MDP with simple transitions and rewards, and a 15 state MDP with random transitions and rewards, then trains every-visit-MC, first-visit-MC (on policy) and off-policy-every-visit-MC to do Value learning.

I had also started working on recognizers but whatever I did on paper doesn't make sense to implement.