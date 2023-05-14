ones = 5
twos = 10
threes = 15
fours = 20
fives = 25
sixes = 30

upper_subtotal = ones + twos + threes + fours + fives + sixes
upper_bonus = 35 if upper_subtotal >= 63 else 0
upper_total = upper_subtotal + upper_bonus

three_of_a_kind = 2
four_of_a_kind = 3
full_house = 20
small_straight = 30
large_straight = 30
yahtzee = 30
chance = 20

total = three_of_a_kind + four_of_a_kind + full_house+ small_straight + large_straight + yahtzee + chance 

scoresheet = f"""========================================
| UPPER SECTION                       |
========================================
| Category        | Score |   Total   |
|-----------------|-------|-----------|
| Ones            | {ones:<6}|           |
| Twos            | {twos:<6}|           |
| Threes          | {threes:<6}|           |
| Fours           | {fours:<6}|           |
| Fives           | {fives:<6}|           |
| Sixes           | {sixes:<6}|           |
|-----------------|-------|-----------|
| Subtotal        |       | {upper_subtotal:<10}|
| Bonus (35)      |       | {upper_bonus:<10}|
|-----------------|-------|-----------|
| Total           |       | {upper_total:<10}|
========================================
| LOWER SECTION                       |
========================================
| Category        | Score |   Total   |
|-----------------|-------|-----------|
| Three of a Kind |       |           |
| Four of a Kind  |       |           |
| Full House      |       |           |
| Small Straight  |       |           |
| Large Straight  |       |           |
| Yahtzee         |       |           |
| Chance          |       |           |
|-----------------|-------|-----------|
| Total           |       |           |
========================================
| GRAND TOTAL                         |
========================================
|                 |       |           |
======================================== """
print(scoresheet)
