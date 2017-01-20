CSC 204 Lab Assignment 1: Moving Tank
===================

What is it?
-------------
Tank Sprite that moves forward, reverses and turns. 

> **Note:**

> - Will be used for following labs
> - Skills gained: reading keyboard events, translating and rotating gameobject


### Logic

```flow
st=>start: Sprite
e=>end: Transformation
op1=>operation: Update
sub1=>subroutine: Check For Key Press
cond=>condition: Key Press (W, A, S, D)
c2=>condition: Good idea|rejected
io=>inputoutput: catch something...|future
op2=>operation: Rotation/Translation


st->op1(right)->cond->
cond(yes)->op2
cond(no)->op1


```
### More Information

> **Note:** You can find more information:

> - about the **Course** [here][1],
> - about the **Lab**  [here][2]
> - about the rock star **Instructors**  [Dr. Tagliasacchi][3], [Dr. Tarini][4]

  [1]: https://heat.csc.uvic.ca/coview/outline/2017/Spring/CSC/205
  [2]: https://github.com/ataiya/igd/wiki/Lab00_TankMoving
  [3]: http://gfx.uvic.ca/people/ataiya/
  [4]: http://vcg.isti.cnr.it/~tarini/

