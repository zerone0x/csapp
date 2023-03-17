normalized encode:
![](https://i.imgur.com/3b1xN9r.png)

![](https://i.imgur.com/AAQI6oc.png)

```
E = Exp - Bias
0 <= Exp <= 255 2^8-1
-127 <= E <= 128
```

![](https://i.imgur.com/DPJNM8G.png)

![](https://i.imgur.com/iNr9epT.png)

140 127 how these num come out 
> However, to allow for both positive and negative exponents, a bias value is subtracted from the stored exponent value to determine the actual exponent value.
> So, in summary, "Exp" is the value stored in the exponent field, and "Bias" is a fixed value that is added to or subtracted from the exponent field value to get the actual exponent value.

![](https://i.imgur.com/IqwD95l.png)

**Violates associativity /distributivity**




