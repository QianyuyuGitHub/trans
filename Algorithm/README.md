### Q
'''python
accum("abcd")    # "A-Bb-Ccc-Dddd"
accum("RqaEzty") # "R-Qq-Aaa-Eeee-Zzzzz-Tttttt-Yyyyyyy"
accum("cwAt")    # "C-Ww-Aaa-Tttt"
'''

### A
'''python
def accum(s):
    return '-'.join(c.upper() + c.lower() * i for i, c in enumerate(s))
'''


### Q
'''python
given a string of words, return the length of the shortest word(s).

test.describe("Basic Tests")
test.assert_equals(find_short("bitcoin take over the world maybe who knows perhaps"), 3)
test.assert_equals(find_short("turns out random test cases are easier than writing out basic ones"), 3)
test.assert_equals(find_short("lets talk about javascript the best language"), 3)
test.assert_equals(find_short("i want to travel the world writing code one day"), 1)
test.assert_equals(find_short("Lets all go on holiday somewhere very cold"), 2)

'''

### A
'''python
def find_short(s):
    return min(len(x) for x in s.split())
'''

'''python
def find_short(s):
    return min(map(len, s.split(' ')))
'''


### Q
'''python
digital_root(16)
=> 1 + 6
=> 7

digital_root(942)
=> 9 + 4 + 2
=> 15 ...
=> 1 + 5
=> 6

digital_root(132189)
=> 1 + 3 + 2 + 1 + 8 + 9
=> 24 ...
=> 2 + 4
=> 6

digital_root(493193)
=> 4 + 9 + 3 + 1 + 9 + 3
=> 29 ...
=> 2 + 9
=> 11 ...
=> 1 + 1
=> 2
'''

### A
'''python
def digital_root(n):
    return n if n < 10 else digital_root(sum(map(int,str(n))))
'''