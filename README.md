```rs
struct Myself {
    name: String,
    age: u8,
    bio: String,
    socials: Vec<String>,
    website: String,
}

fn about_me() -> Myself {
    Myself {
        name: "Rithul Kamesh".to_string(),
        age: 16,
        bio: r#"
        👋 Hey There! I'm Rithul, a 16 year old Student and Developer who loves everything Rust and Node.js, Currently, I'm building a suite of productivity apps with both of them! Me also learning Flutter to port them to mobile! I think that programming is awesome and I love to code/program a ton! Aside from that, I am a huge weeb and an avid manga reader.
        "#
        .to_string(),
        socials: vec![
            String::from("https://twitter.com/rithulkamesh"),
            String::from("https://polywork.com/rithul")
        ],
        website: "https://rithul.dev".to_string()
    }
}
```
