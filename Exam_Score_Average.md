# Exam Score Average


```python
#Entering how many exams you have done
```


```python
num_of_exams= int(input("Enter the number of your exams: "))
```

    Enter the number of your exams: 3



```python
# Entering how many these credits cover
```


```python
total_credits= int(input("Enter the number of credits your exams cover: "))
```

    Enter the number of credits your exams cover: 10



```python
# Start with average 0 and then add other percentages:
```


```python
average= 0
```


```python

for exam in range(num_of_exams):
    score= int(input("Enter your exam score: "))
    exam_credits= int(input("Enter how many credits this score covered "))
    average= average+ score*exam_credits/total_credits
print(average)

```


```python
print(average)
```

    6.0



```python

```
