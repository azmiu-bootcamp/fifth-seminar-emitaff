https://classroom.github.com/a/m6-RxH9f - bu linkdən istifadə edərək məsələri öz github-nıza ələvə edin.

**Condition exercises**
1. Verilmiş 3 ədəddən bir-birinə bərabər olanların sayını tapın

2. Verilmiş funksiyanı elə tamamlayın ki, qeyd olunan şərtlər ödənsin:
- **a** və ya **b** -dən hər hansı biri **6**-dırsa, funksiya True qaytarsın
- və ya **a** və **b** -nin cəmi və ya fərqi **6**-dırsa, funksiya True qaytarsın
- digər bütün hallarda funksiya False qaytarsın <br />
**Qeyd:** abs(num) funksiaysı num ədədinin mütləq qiymətini tapır.
```
# funksiyanın ardını tamamlayın
def love6(a, b):

```
**Nümunə:**
```
love6(6, 4) → True
love6(4, 5) → False
love6(1, 5) → True
```
3. Verilmiş a, b, c ədədlərinin cəmini tapın. Əgər bu ədədlərdən bir və ya bir neçəsi bərabərdirsə, onda onları cəmdə nəzərə almayın.

```
# funksiyanı tamamlayın
def lone_sum(a, b, c):
```
**Nümunə**
```
lone_sum(1, 2, 3) → 6
lone_sum(3, 2, 3) → 2
lone_sum(3, 3, 3) → 0
```
**Loop exercises**
4. Verilmiş ədədin polindrom olub olmadığını yoxlayın.
```
# ardını siz tamamlayın
func isPolindrome(num):
```
**Nümunə**
```
isPolindrome(1234321) -> True
isPolindrome(45345) -> False
```
5. Verilmiş massivdə ən maksimal elementə bərabər neçə ədəd var.

**Nümunə**
```
m = [1, 7, 9, 0] -> 1
m = [1, 3, 3, 1, 0] -> 2
```

6. Verilmiş massivdə özündən əvvəlki elementdən böyük elementləri çap edin.
**Nümunə**
```
1, 5, 2, 4, 3 -> 5, 4

-9, 29, -100, 64, 26, 73, -96, 28, -92, 11, -14, -86, -54, -67 -> 29, 64, 73, 28, 11, -54
```
7. Verilmiş massivdə qonşu elementlərin yerini dəyişin. Tutaq ki, A massivi verilib. Onda A[0] ilə aA[1] - in, A[2] ilə A[3] - ün yerini dəyişin.

**Nümunə** 
```
1 2 3 4 5 -> 2 1 4 3 5

9 4 5 2 3 -> 4 9 2 5 3
```

8. Tic-tac-toe oyunu hazırlamaq.
