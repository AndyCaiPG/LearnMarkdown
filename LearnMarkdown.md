# Markdown

# h1
## h2
### h3
#### h4
##### h5
###### h6
### Directory
[toc]
### Body
This is body
This
is
body
### Hello, world!
```
Hello, world!
 Hello, world!
  Hello, world!
```
### C++ code
```c++
int main()
{
    std::cout<<"Hello,world!"<<std::endl;
    return 0;
}
```
### Python code
```python
if __name__ == "__main__":
    print("Hello, world!")
```
### C code
```c
int main()
{
    printf("Hello, world!");
    return 0;
}
```
### PowerShell code
```powershell
echo "Hello, world!"
```
### Bash code
``` bash
echo Hello, world!
```
### sh code
```sh
printf '%s\n' "Hello, world!"
```
### Code within the body
This is body ``std::cout<<"Hello, world!"<<std::endl;`` this is body
### Marker within the body
This is body `marker marker marker` this is body
### Block
This is body

    Hello, world!
     Hello, world!
      Hello, world!
        Hello, world!
    Hello, world!
### Ordered List
1. First
2. Second
3. Third
    1. first
    2. second
    3. third
        1. first
        2. second
        3. third
            1. first
            2. second
            3. third
### Disordered List
- Hello
- Hello
- Hello
    - Hello
    - Hello
    - Hello
        - Hello
        - Hello
        - Hello
            - Hello
            - Hello
            - Hello

* Hello
* Hello
* Hello
    * Hello
    * Hello
    * Hello
        * Hello
        * Hello
        * Hello
            * Hello
            * Hello
            * Hello
### Option list
- [x] option 1
- [ ] option 2
- [x] option 3
- [ ] option 4
### quote
> This is quote
This is quote
This is quote
> This is quote
> This is quote
>> this is quote
this is quote
>> this is quote
this is quote
>>> this is quote
this is quote
>> this is quote
> This is quote
> This is quote
This is quote
This is quote
### Link
[Google](https://www.google.com/ "Google")

[Bing](https://www.bing.com/ "Bing")

[Github](https://github.com/ "Github")
### Image
![](./image/LionelMessi.jpg 'Lionel Messi')

![](./image/StephenChow.jpg 'Stephen Chow')

![](./image/JayChou.jpg 'Jay Chou')

![](./image/JackyCheung.jpg 'Jacky Cheung')

![](./image/FootballGame.gif 'football game')

![](./image/Programmer.jpg 'Programmer')
### Image with link
[![](./image/Google.jpg 'Google')](https://www.google.com)

[![](./image/Bing.jpg 'Bing')](https://www.bing.com)

[![](./image/Github.jpg 'Github')](https://github.com)
### Table
title 1|title 2|title 3
:-:|:-|-:
center|align left|align right
a|b|c
a|b|c
a|b|c
a|b|c
### Font
*italic*
_italic_
**bold**
***bold&italic***
**_bold&italic_**
~~delete line~~
### Separator line
***
---
* * *
### Arithmetic formula
center
$$x+y$$
align left
$x+y$
$$x+y$$
$$x-y$$
$$x \pm y$$
$$x \mp y$$
$$x * y$$
$$x \ast y$$
$$x \times y$$
$$x \cdot y$$
$$x/y$$
$$x \div y$$
$$x+y=z$$
$$x+y>z$$
$$x+y<z$$
$$x+y \geq z$$
$$x+y \leq z$$
$$x+y \neq z$$
$$x+y \ngeq z$$
$$x+y \not \geq z$$
$$x+y \nleq z$$
$$x+y \approx z$$
$$x+y \equiv z$$
$$\frac {x+y}{y+z}$$
$${x+y} \over {y+z}$$
$$|x+y|$$
$$\overline{xyz}$$
$$\sqrt x$$
$$\sqrt[3]{x+y}$$
$$\log x$$
$$\lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$
$$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$
$$\int^{\infty}_{0}{xdx}$$
$$\frac{\partial x}{\partial y}$$
$$\left[ \begin{matrix} 1 & 2 & \cdots & 4 \over 5 & 6 & \cdots & 8 \\ \vdots & \vdots & \ddots& \vdots & \vdots & & \vdots \\5 & 6 & \cdots &13 &14 &\cdots &16\end{matrix} \right]$$
$$x \in y$$
$$x \notin y$$
$$x \not \in y$$
$$x \subset y$$
$$x \supset y$$
$$x \subseteq y$$
$$x \subsetneq y$$
$$x \not \subset y$$
$$x \cup y$$
$$x \cap y$$
$$x \setminus y$$
$$x \bigodot y$$
$$x \bigotimes y$$
$$\mathbb{R}$$
$$\mathbb{Z}$$
$$\emptyset$$
$$\infty$$
$$\imath$$
$$\jmath$$
$$\hat{a}$$
$$\check{a}$$
$$\breve{a}$$
$$\tilde{a}$$
$$\bar{a}$$
$$\vec{a}$$
$$\acute{a}$$
$$\grave{a}$$
$$\mathring{a}$$
$$\dot{a}$$
$$\ddot{a}$$
$$\uparrow$$
$$\Uparrow$$
$$\downarrow$$
$$\Downarrow$$
$$\leftarrow$$
$$\Leftarrow$$
$$\rightarrow$$
$$\Rightarrow$$
$$1,2,\ldots,n$$
$$x_1^2 + x_2^2 + \cdots + x_n^2$$
$$\vdots$$
$$\ddots$$
$$\alpha$$
$$\beta$$
$$\Gamma$$	
$$\gamma$$
$$\Delta$$
$$\delta$$
$$\epsilon$$
$$\zeta$$
$$\eta$$
$$\Theta$$
$$\theta$$
$$\iota$$
$$\kappa$$
$$\Lambda$$	
$$\lambda$$
$$\mu$$
$$\nu$$
$$\Xi$$	
$$\xi$$
$$\omicron$$
$$\Pi$$	
$$\pi$$
$$\rho$$
$$\Sigma$$
$$\sigma$$
$$\tau$$
$$\Upsilon$$	
$$\upsilon$$
$$\Phi$$	
$$\phi$$
$$\chi$$
$$\Psi$$	
$$\psi$$
$$\Omega$$
$$\omega$$
### Email
<email@gmail.com>
### Footnote
Hello[^1],world[^2]!
[^1]: This is a footnote
[^2]: This is another footnote
### Anchor
[An anchor](#1)
[Another anchor](#2)
###### Directory that needs to jump {#1}
###### Directory that needs to jump {#2}
### Defined list
Hello, word!
:   This is defined list!
### Flow diagram
```flow                    
st=>start: START|past:> https://www.bing.com[_blank]
e=>end: END            
c1=>condition: condition1|past:>https://www.baidu.com[_parent]
c2=>condition: condition2|past:>https://github.com[_parent]   
c3=>condition: condition3|past:>https://stackoverflow.com[_blank]
io=>inputoutput: output|past:>https://www.w3school.com.cn[_blank]
st->c1(yes,right)->c2(yes,right)->c3(yes,right)->io->e
c1(no)->e                   
c2(no)->e                   
c3(no)->e                   
```
```flow                          
st=>start: START|past:>https://www.bing.com[_blank]
e=>end: END                  
op1=>operation: plan1|approved:>#1         
sub2=>subroutine: plan2|approved:>#2
sub3=>subroutine: replan|past:>https://www.google.com[_blank]
cond1=>condition: Is it feasible? 
cond2=>condition: Is it feasible?        
io=>inputoutput: ok          
st->op1->cond1
cond1(no,left)->sub2(bottom)->cond2(no,right)->sub3(right)->op1
cond1(yes)->io->e   
cond2(yes)->io->e
```
### Sequence diagram
``` sequence
Boy->Girl: Hello!
Note left of Boy: Say
Note right of Girl: Answer
Girl-->Boy: Hi!
```
```sequence
Get up->>Have breakfast: Bread and milk
Have breakfast-->>Get up: Eat full
Get up->Go to work: By subway
Go to work->>Have lunch: Pasta
Have lunch-->>Go to work: Eat full
Go to work->Get off work:
Get off work->Go home: By subway
Go home->Sleep: Feeling sleepy
Note right of Sleep: The end of the day!
Sleep-->Get up:
Note left of Get up: A new day!
```