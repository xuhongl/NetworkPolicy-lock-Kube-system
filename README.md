# NetworkPolicy-lock-Kube-system

By all means using Network Policy to lock down kube-system is not a MSFT recommended aprroach, not only for the reason that Network Policy should only be used to secure wast-west traffic rather than north/south, but also restricting traffic in and out kube-system is not appropraite as well. 

However if clients have no other options, be sure a set of well crafted policies will be applied. That's the purpose of this repo.
