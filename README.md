# Coding Guidlines
=================

This is the great story of how the awesome people at synoa write their code. 

## Indentation

You should use 2 spaces and maybe 4 if your CTO allows it (which he won't). 

## Comments

### Big

Describe the method, class or what ever parent element with a "big" comment. 

```
/*
 * [<Author>] - #<CallID>: <Comment>
 */
public function foo() {}
```

### Small

If you changed something inside e.g. a method, you write "small" comments at the beginning of the changed line(s).

```
public function foo() {
  // [<Author>] - #<CallID>: <Comment>
  $bar = array();
}
```
