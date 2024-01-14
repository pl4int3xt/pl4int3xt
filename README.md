
```rust
struct Whoami {
    name: String,
    tech_stack: Vec<String>,
}

impl Whoami {
    fn new() -> Self {
        Whoami {
            name: String::from("pl4int3xt"),
            tech_stack: vec![
                String::from("Android Engineer"),
                String::from("Offensive security"),
                String::from("CTF player @p3rf3ctr00t"),
                String::from("Rustacean")
            ],
        }
    }
}

```
