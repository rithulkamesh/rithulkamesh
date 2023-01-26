```rs
struct Myself {
    name: &str,
    age: u8,
    bio: &str,
    socials: &str,
    website: &str,
}

fn about_me() -> Myself {
    Myself {
        name: "Rithul Kamesh",
        age: 16,
        bio: r#"
        👋 Hey There! I'm Rithul, a 17 year old Student and Developer who loves everything Rust and Node.js.
        I think that programming is awesome and I love to code/program a ton! Aside from that, I'm building a game
        with godot just to have fun!
        "#,
        socials: "https://bento.me/rithul"
        website: "https://rithul.dev"
    }
}
```
