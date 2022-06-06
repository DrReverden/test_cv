# Sinichkina Anna Alexandrovna
---

![Avatar from GitHub](89651330.png)

### Contacts

* Phone number
   + 8 (915) 055 88 80
* Email
   + lamafon@mail.ru
* Discord account
   + @DrReverden

### Profile

Interested in exploring a new sphere of activity. I'm not afraid to take on difficult tasks. I dream of developing in a new profession and I want to improve my coding skills.

### Experience 
* 2020 Web-Design School of Nickita Bruskov
* 2020 Web Design Way by Andrew Gavrilow
* 2021 Stepick Cource, JetBrains School, Python for beginners
* 2021 Stepick Course, Web development for beginners

### Code Example
>The program receives a sequence of ten numbers. Then it determines whether each of them is even or not.

```
counter = 0

for i in range(1, 11):
   n = int(input())
   if n % 2 == 0:
      counter += 1
   if counter == 10:
      print('YES')
   else:
      print('NO')
```
> The input to the program is a number *n*, and then *n* lines containing integers in ascending order. The program merges lists of numbers into one sorted list.

```
def quick_merge(list1, list2):
   result = []

   p1 = 0
   p2 = 0
   while p1 < len(list) and p2 < len(list2):
      if list1[p1] <= list2[p2]:
         result.append(list1[p1])
         p1 += 1
      else:
         result.append(list2[p2])
         p2 += 2
   if p1 < len(list1):
      result += list1[p1:]
   if p2 < len(list2):
      result += list2[p2:] 
   return result

total_list = []

for i in range(int(input())):
   num = [int(q) for q in input().split()]
   total_list = quick+merge(total_list, num)
print(*total_list)
```
> Work with Markdown

`https://github.com/DrReverden/rsschool-cv.git`

