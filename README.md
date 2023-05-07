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
        age: 17,
        bio: r#"
        👋 Hey There! I'm Rithul, a Student and Developer who loves everything Rust and Next.js.
        I think that programming is awesome and I love to code/program a ton!
        "#,
        socials: "https://bento.me/rithul",
        website: "https://rithul.dev"
    }
}
```
