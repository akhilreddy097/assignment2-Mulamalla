# assignment2-Mulamalla

# Akhil Kumar Reddy Mulamalla

### Goa

Over a third of Goa is covered by forest. **There are almost 7,000 bars to choose from Goa**   It is the smallest state in India. **Goa is one of India's wealthiest states**, largely thanks to its booming tourist industry.**This beautiful state has also been ranked as the best placed in terms of infrastructure**

***

# Directions From Maryville To Las vegas

1. First start to Kansas 
2. From Kansas we have to go through Colorado to get to Utah
3. Then within few hours we reach St.George
    1. Passing from Little field 
    2. Also from Scenic
4. Then travel on the road between Moapa and Crystal
5. Then finally you can see exotic racing far away which means you finally reached Las Vegas

# Extra Items To Carry 

* Phone
* Sunscreen
* Umbrella
* Fancy Outfits

---

**[About Myself](AboutMe.md)**

---

# Restuarants, I Preffer Going To



| Item  | Location  | Price  |   
|---|---|---|
|  chicken biryani |mehfil   |13$   |   
|  egg roat |  shah ghouse | 20$  |   
|mutton biryani   |  paradise | 12$  |   
|  egg curry |  paradise |  10$ |

***

# Pithy Quotes

>Nowadays you have to be a scientist if you want to be a killer.
― *Vladimir Nabokov, Lolita*

>It's always darkest before you're blinded by the light.
― *josh stern*

---

# Ternary Search Algorithm

A ternary search algorithm is a technique in computer science for finding the minimum or maximum of a unimodal function. A ternary search determines either that the minimum or maximum cannot be in the first third of the domain or that it cannot be in the last third of the domain, then repeats on the remaining two thirds. A ternary search is an example of a divide and conquer algorithm

Link: <https://en.wikipedia.org/wiki/Ternary_search>

```
double ternary_search(double l, double r) {
    double eps = 1e-9;              //set the error limit here
    while (r - l > eps) {
        double m1 = l + (r - l) / 3;
        double m2 = r - (r - l) / 3;
        double f1 = f(m1);      //evaluates the function at m1
        double f2 = f(m2);      //evaluates the function at m2
        if (f1 < f2)
            l = m1;
        else
            r = m2;
    }
    return f(l);                    //return the maximum of f(x) in [l, r]
}
```
Link: <https://cp-algorithms.com/num_methods/ternary_search.html>

