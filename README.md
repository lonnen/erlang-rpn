An RPN calculator written in erlang

```
1> c(calc).
{ok,calc}

2> calc:rpn_test().
ok

3> calc:rpn("90 34 12 33 55 66 + * - + -").
4037
```
