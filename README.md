# assignment2-Kakunuri
## Hyderabad
I like **Hyderabad** because it is my Home town Other than that  my **family and friends** live there.I have Lots of memories with them in Hyderabad .And one of the best tourism place in **India**.

---

# Travelling Directions from Maryville to Hyderabad

1. Maryville to Hyderabad
    1. Maryville to Kansas City (MCI)
    2. Kansas City to Chicago (ORD)
    3. Chicago to Delhi (IGI)
    4. Delhi to Hyderabad (RGI)

- Mobile Phone
- Airpods
- Cookies
- Chocolates
- Water bottle
- Clothes
- Shoes

[AboutMe](https://github.com/Arunreddy619/assignment2-Kakunuri/blob/main/AboutMe.md)

---
# Food/Drink that I recommend to Friend.

| Food/Drink | Location | Price |
| ---------- | -------- | ----- |
|    Pizza   | Pizzahut |   $5  |
|   Burger   | BurgerKing | $1 |
| Nuggets | McDonalds | $2 |
| softdrink | Dominos | $1.5 | 

---

# Quotes
> - Arise,awake and donot stop until the goal is reached. 
> - You cannot believe in God until you believe in yourself.<br/>
>                                    - By *Swami Vivekananda* 

---
# Code Fencing

>Sqrt (or Square Root) Decomposition Technique is one of the most common query optimization technique used by competitive programmers.  This technique helps us to reduce Time Complexity by a factor of sqrt(n). 
The key concept of this technique is to decompose given array into small chunks specifically of size sqrt(n).

[Source Link](https://www.geeksforgeeks.org/sqrt-square-root-decomposition-technique-set-1-introduction/)

```
// input data
int n;
vector<int> a (n);

// preprocessing
int len = (int) sqrt (n + .0) + 1; // size of the block and the number of blocks
vector<int> b (len);
for (int i=0; i<n; ++i)
    b[i / len] += a[i];

// answering the queries
for (;;) {
    int l, r;
  // read input data for the next query
    int sum = 0;
    for (int i=l; i<=r; )
        if (i % len == 0 && i + len - 1 <= r) {
            // if the whole block starting at i belongs to [l, r]
            sum += b[i / len];
            i += len;
        }
        else {
            sum += a[i];
            ++i;
        }
}

```

[Code Link](https://cp-algorithms.com/data_structures/sqrt_decomposition.html)

## Hi there!
🐻   **I am bearcat** <br/>
🐱 **This is Meercat** 
