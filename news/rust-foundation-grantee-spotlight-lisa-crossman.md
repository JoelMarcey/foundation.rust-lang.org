---
title: 'Community Grantee Spotlight: Lisa Crossman'
byline:
description: >-
  Meet Lisa Crossman: A Rust Foundation Project Grantee under the Community
  Grants Program — and the latest subject of our Community Grantee Spotlight
  series.
date: 2023-05-25T12:00:00Z
tags:
  - grantee spotlight
  - community grants
  - programs
index: false
layout: layouts/news.njk
---
<img src="/img/news/2023-05-25-lisa-crossman-grantee-spotlight/lisa-crossman.png" width="580" height="326" alt="Community Grantee Spotlight: Lisa Crossman" title="Community Grantee Spotlight: Lisa Crossman" />

> *<u>About this series</u>*
>
> *Welcome to the Rust Foundation’s latest installment of the Community Grantee series – a collection of blogs that will highlight the accomplishments and experiences of individuals who received a [<u>Project Grant</u>](https://foundation.rust-lang.org/grants/project-grants/) or [<u>Rust Foundation Fellowship</u>](https://foundation.rust-lang.org/grants/fellowships/) as part of our [<u>Community Grants Program</u>](https://foundation.rust-lang.org/grants/). Each installment features an interview with an individual grantee about their progress, goals, and experiences in the program.&nbsp;*
>
> *Our intention for this series is to celebrate our hardworking grantees while shedding light on the wide breadth of work they are collectively doing to benefit the Rust ecosystem. We hope you enjoy getting acquainted with these amazing individuals!*
>
> *Note: This series will not function as a comprehensive catalog of all our grantees, but instead will highlight a handful of individuals who expressed interest. Please stay tuned for a new page our team is working on that will list the grants we’ve issued to date. In the meantime, you can find our most recent announcement of Rust Foundation grants [<u>here</u>](https://foundation.rust-lang.org/news/community-grants-program-awards-announcement-introducing-our-latest-project-grantees/) – with more to be announced soon!&nbsp;*

---

## ***The Grant:***&nbsp;

Rust Foundation Project Grant (Awarded in June 2022)&nbsp;

[***<u>&gt;&gt;Learn more about this grant</u>***](https://foundation.rust-lang.org/grants/project-grants/)

## ***<u>The Grantee:</u>***

<u>Name:</u> Lisa Crossman

<u>Location:</u> Norwich, Norfolk in East of England&nbsp;

<u>Pronouns:</u> She/Her&nbsp;

<u>Fun fact:</u>&nbsp;"My voice is featured on a CD singing with 6000 other people as part of Gareth Malone’s Great British Home Chorus with the London Symphony Orchestra."

## ***<u>The Work:&nbsp;</u>***

### **Focus of work under the Grants Program:**

*To raise Rust’s profile in bioinformatics & improve bioinformatics methods in gene finding*.

## ***<u>The Conversation:&nbsp;</u>***

### ***<u>Q: Tell us a bit about yourself and your background.</u>***

A: I'm a freelance bioinformatician. Prior to embarking on the path I’m currently on, I was actually a lab scientist working on microbiology, with a specific focus on bacteria.&nbsp;

Over the years, I began working more in the bacterial genomics field. In my work, I was constantly running other people’s programs in the lab and they could never do quite what I needed them to, so I gradually learned to program and build my own solutions. My programming motivation was originally to tweak these other programs in small ways to customize them to do what I needed. Over time, others began coming to me to ask if I could spin up small programs to solve problems in the lab. I started out with Python and R.&nbsp;

### ***<u>Q: Tell us more about the field you work in.</u>***

Genomics involves identifying and studying the genes in a sequence. In order to do this, you need to be able to identify where the gene begins and ends within the sequence and then you’re able to get an idea of what they do.&nbsp;

Over the years, many scientists have been working in this arena. When the field emerged, the gene sequencing process was manual. Later, bioinformaticists began using a Java program that would require you to spend a year on a single genome – typing where the start and stop of the gene was and what you thought it did. This work (usually called computational biology) requires you to rely on deep knowledge of biology and a lot of literature.&nbsp;

Eventually, there were just too many genomes being studied for this approach to make sense and people started investigating automation possibilities.

In my research, I discovered that many computational biologists are relying on agene prediction software, which is a bit old now because it's from 2010. Everyone is relying on this one piece of software, so if it makes a mistake, it’s going to get propagated through swathes of data sets. The software is particularly prone to error when the genes are a bit atypical. This is especially a risk in bacterial genomes for reasons I won’t go into here.&nbsp;

This risk of error is actually quite concerning because everyone in this field is relying on the software. All the data generated by this older software goes back to DNA sequencing databases, which is then downloaded and used by others. As you can gather, sequencing errors have global research ramifications.&nbsp;

I’ve been thinking about this issue for a long time and encountering it frequently in my work. There was a particularly long and atypical gene that kept getting missed by the gene prediction software. This gene happens to be really pivotal for infection prediction and a motivation to stop this issue from happening was what prompted me to consider spinning up my own software.&nbsp;

After doing some initial research and work on this project, I&nbsp; realized that fast programming is the key to faster and more accurate sequencing work and I wondered if there was a way to improve or replace the existing software we use. If not, perhaps there was a tool that could be created to work in conjunction with the existing software, helping it show errors better.

### ***<u>Q: How did you land on Rust to help solve this challenge?</u>***

One day, my collaborator asked me to create a program to count kmers (very short pieces of a DNA sequence) very quickly to solve a specific bacterial genome problem we were working on. I initially thought that it wouldn’t be possible to accomplish this at the speed he was requesting. But I did some research into efficient programming languages and after considering a few other languages, I landed on using Rust.&nbsp;

### ***<u>Q: Tell us about the process of getting started with Rust.</u>***

A: I must admit that it was difficult to find a starting point with Rust, but that's actually normal in bioinformatics anyway. I was used to working without a map. In my opinion, jumping in with both feet is the first thing you need to be prepared to do when learning Rust.&nbsp;

The only way I could really get started was to sift through source code and try things out. Obviously, if you don't understand the source code at all, that's quite a difficult thing to do! But [<u>Rust Playground</u>](https://play.rust-lang.org/?version=stable&amp;mode=debug&amp;edition=2021) really helped me in the early stages because you could actually get some things to work without having to compile it and spend ages learning Cargo right out of the gate.

### ***Q: What prompted you to apply for the Rust Foundation’s Community Grants Program?***

Because I’m a freelancer, I suppose I was in one of those lull periods where I was looking for things to do and new projects to take on. I was researching Rust grants and research opportunities and I found the program that way. When I read more about the Rust Foundation and saw that the application wasn’t enormously long, I decided to go ahead and apply. To be honest, I didn't expect anything to come of my application because I come from the bioinformatics field, and I wasn't really sure if that's where the Foundation wanted to direct funding. Even so, I figured I didn’t have much to lose.&nbsp;

### ***Q: What are you most proud of having accomplished under the program?&nbsp;***

Hundreds of lines of code – that ran! I also discovered I was a Rustacean all along, even down to being mostly harmless.

### ***Q: What was your experience as a grantee like overall?&nbsp;***

The program has a really nice community feel and I feel well-supported. I will say that by and large, the other grantees are a bit less chatty than I am but then again, I come from a lab environment where biologists are *very* chatty! Overall, it has been a fantastic experience.&nbsp;

### ***Q: Name one new thing about Rust that you’ve learned from your work under the program.***

I actually learned a ton of Rust during this program. Being a Rust Foundation Grantee probably increased my knowledge hugely, so it's difficult to name one thing that I learned.&nbsp;

I suppose one thing I was surprised by is that Rust can actually be more like Python than I initially thought. You can kind of get away with not writing loads of structs and traits. Similar to Python, once you have foundational Rust knowledge, it’s simple to get on with.&nbsp;

### ***Q: What would you tell someone who is interested in applying for the Grants Program but is unsure about whether or not they “should”?&nbsp;***

I’d tell someone in this position that I always have the feeling that I'm in the wrong place and doing the wrong thing all the time. In recent years, I’ve reframed this feeling and the limiting belief that comes from it like this: because I am always doubting myself, trying a different thing (like applying for a grant) doesn't actually make any difference.&nbsp;

My message to prospective Rust Foundation grantees is just to give it a go and try to avoid second-guessing yourself.&nbsp;&nbsp;

### ***Q: Any advice for the next round of applicants to our program?***

As general advice, please contribute to Rust– both in terms of documentation and the community to help build a great ecosystem!

### **Q: If you had to pick one word (or maybe a few!) to describe your experience under the Community Grants Program, what would it be?&nbsp;**

Opportunity

### **Q: What excites you most about Rust/the future of Rust/the implications of Rust?&nbsp;**

Rust has huge potential for growth and is up-and-coming and forward-looking.&nbsp; With all this promise it should be the programming language of choice for the next generation of software! &nbsp;

---

Thank you to Lisa for taking the time to chat with our team about their work under the Community Grants Program so far! We’re excited to publish more installments of our Grantee Spotlight Series in the near future. You can follow the development of the series [<u>here</u>](https://foundation.rust-lang.org/tags/grantee%20spotlight%20series).&nbsp;

Lisa will be speaking about her work at RustConf 2023 coming up in September in Albuquerque, NM and online. Learn more and register <a target="_blank" rel="noopener" href="https://rustconf.com/speakers/lisa-crossman">here</a>.&nbsp;

---

### ***About the Rust Foundation Community Grants Program***

The Rust Foundation [<u>Community Grants Program</u>](https://foundation.rust-lang.org/grants/) provides access to new resources for the Rust community to maintain, innovate, collaborate over, and further develop the Rust programming language. While the Community Grants Program provides financial backing across several different categories (Events Support Grants, Rust Foundation Fellowships, Hardship Grants, and Project Grants) the overall mission is shared: to support the continued expansion of Rust and address key areas for development across the Rust ecosystem. The Rust Foundation Community Grants Program is made possible by <a target="_blank" href="https://aws.amazon.com/">AWS</a>, [Huawei](https://www.huawei.com/en/), [Google](https://www.google.com/), and [Zama](https://www.zama.ai/). Learn more about the program [<u>here</u>](https://foundation.rust-lang.org/grants).&nbsp;