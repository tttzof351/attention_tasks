# Attention tasks

Original: https://github.com/greentfrapp/attention-primer

## Task 1

The task is to write a count of the number of elements of a fixed-size sequence consisting of characters A, B, C
```
[A, B, B, C] ->  { A:1, B:2, C:1 }
[A, B, B, A] ->  { A:2, B:2, C:0 }
```

## Task 2

The task is to write a count of the number of elements of a sequence of a fixed size consisting of characters A, B, C and the absolute difference of counters A - B

```
[A, B, B, C] ->  { A:1, B:2, C:1, A_DIFF_B: 1 }
[A, B, B, A] ->  { A:2, B:2, C:0, A_DIFF_B: 0 }
```

## Task 3

The task is to write a count of the number of first element (not including this element) in a sequence of a fixed size consisting of the characters A, B, C

```
[A, B, B, C] ->  { A:0 }
[B, B, A, C] ->  { B:1 }
```

## Task 4

The task is to write a count of the number of first elements (not including this element itself) in a fixed-size sequence consisting of the characters A, B, C

```
[A, B, B, C] ->  { A:0, B: 1, C: 0 }
[C, B, B, B, A, B, C] ->  { C: 0, B: 2: B: 2 }
```

## Task 5

The taks is to write a translator from German to English using IWSLT 2016 de-en dataset

