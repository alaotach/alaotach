## About Me

```rust
use std::collections::HashMap;

struct Aryan;

struct Attributes;

impl Attributes {
    fn contact() -> (&'static str, &'static str, &'static str, &'static str) {
        let telegram = "t.me/mrmango42";
        let instagram  = "instagram.com/alaotach";
        let linkedin  = "linkedin.com/in/alaotach";
        let email    = "alaotach@gmail.com";
        (telegram, instagram, linkedin, email)
    }

    fn life() -> (Vec<&'static str>, u8) {
        let langs = vec!["English", "Hindi"];
        let age: u8 = 19
        (langs, age)
    }

    fn coding() -> (
        HashMap<&'static str, Vec<&'static str>>,
        Vec<&'static str>,
        Vec<&'static str>,
        HashMap<&'static str, HashMap<&'static str, HashMap<&'static str, &'static str>>>,
    ) {
        let mut langs: HashMap<&str, Vec<&str>> = HashMap::new();
        langs.insert("expert", vec!["python", "typescript"]);
        langs.insert("intermediate", vec!["java", "c++", "rust", "go"]);
        langs.insert("learning", vec!["solana", "blockchain dev"]);

        let specialities = vec!["AI/ML", "blockchain", "fullstack", "app & web dev"];
        let ide = vec!["vscode", "neovim"];

        let mut pc: HashMap<&str, HashMap<&str, HashMap<&str, &str>>> = HashMap::new();

        let mut arch = HashMap::new();
        let mut specs = HashMap::new();
        specs.insert("processor", "12th Gen Intel(R) Core(TM) i5-12450H (12) @ 4.40 GHz");
        specs.insert("ram", "16gb");
        specs.insert("gpu", "NVIDIA GeForce RTX 3050 Mobile");
        arch.insert("custom", specs);

        pc.insert("Linux", arch);

        (langs, specialities, ide, pc)
    }
}

fn main() {
    let contact = Attributes::contact();
    let (languages, age) = Attributes::life();
    let (langs, specialities, ide, pc) = Attributes::coding();

    println!("Contact: {:?}", contact);
    println!("Languages: {:?}, Age: {}", languages, age);
    println!("Coding langs: {:?}\nSpecialities: {:?}\nIDE: {:?}\nPC: {:?}", langs, specialities, ide, pc);
}
```

> *Building AI, machine learning, and blockchain projects.*
> *Founder of EryzaLabs.*

---

## Skills

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,rust,js,react,java,cpp,solidity,html,css" alt="skill icons" />
  </a>
</p>

---

## Live Widgets

<p align="center">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=alaotach&theme=tokyonight&show_icons=true" />
</p>

<!--START_SECTION:WAKA-->
<!--END_SECTION:WAKA-->

```text
💾 Languages:
C#                12h 51m 0s   █████████████░░░░░░░░░░░░  48.96%
unity             12h 48m 0s   █████████████░░░░░░░░░░░░  48.74%
XML               1h 45m 0s    ██░░░░░░░░░░░░░░░░░░░░░░░  6.70%
TypeScript        1h 30m 0s    ██░░░░░░░░░░░░░░░░░░░░░░░  5.74%
JavaScript        36m 0s       █░░░░░░░░░░░░░░░░░░░░░░░░  2.31%
Markdown          27m 0s       █░░░░░░░░░░░░░░░░░░░░░░░░  1.73%
Java Properties   17m 0s       █░░░░░░░░░░░░░░░░░░░░░░░░  1.11%
Kotlin            16m 0s       █░░░░░░░░░░░░░░░░░░░░░░░░  1.06%
JSON              14m 0s       █░░░░░░░░░░░░░░░░░░░░░░░░  0.91%
Other             8m 0s        █░░░░░░░░░░░░░░░░░░░░░░░░  0.56%

💼 Projects:
```
---

## Quick Links

* LinkedIn: [https://linkedin.com/in/alaotach](https://linkedin.com/in/alaotach)
* GitHub: [https://github.com/alaotach](https://github.com/alaotach)
* Email: [alaotach@gmail.com](mailto:alaotach@gmail.com)

---

## Contributing & License

This README is a personal profile. If you want to borrow or adapt styling/code, go ahead â€” give credit if you copy large parts. No special license attached here; treat this as creative personal content.

---
