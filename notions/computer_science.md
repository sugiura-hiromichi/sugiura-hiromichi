|Shell
---

# Symbolic link tip

When you use 'ln -s', arguments have to be **absolute** path. Make sure that not relying on current path.

# Useful Shell variable
- XDG_CONFIG_HOME (default is $HOME/.config/)

# `date`
`date` command prints current time, day, year, day of the week on certain time zone
 
# Makefile

`Makefile` is make's config file. Make sure that name is not `MakeFile`. This simply unable to work

# LLDB

lldb's help is very useful. Use actively. [useful link](https://qiita.com/theefool/items/8b985ce71dcdccf26abc)

## CheatSheet



|Rust
---

# `pub(path to target)` conjunction

>see [official reference](https://doc.rust-lang.org/reference/visibility-and-privacy.html#pubin-path-pubcrate-pubsuper-and-pubself), [related error](https://doc.rust-lang.org/error-index.html)

`pub` has attatchment like `pub(attatchment)`.  
This signifies where to `pub`. 

>**Edition Guide**  
>Since 2018 editon, *path* for `pub(in *path*)` must start with `crate`, `super`.

For example,

```rust
pub mod mod1{
   pub mod mod2{
      pub mod mod3{}
      pub(crate) fn visible_within_same_crate(){}
      pub(super) fn visible_within_mod2(){}
      pub(in crate::mod1) fn visible_within_mod1(){}
   }
}
```

---
