# Coding Guidlines
=================

This is the great story of how the awesome people at synoa write their code. 

## Indentation

You should use 2 spaces and maybe 4 if your CTO allows it (which he won't). 

## Comments

### Basic elements

<table>
<tr><th>&lt;Author&gt;</th><td>JohnDoe</td></tr>
<tr><th>&lt;CallID&gt;</th><td>1337</td></tr>
<tr><th>&lt;Comment&gt;</th><td>This and that was changed</td></tr>
</table>


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

### Hints

1. If you don't have a CallID, you should probably create a call. If there is no reason to create a call, you can write the comment like this: `[<Author>] - <Comment>`
2. If you need more than one line to describe something inside e.g. a method, you can switch to "big" comments. 
