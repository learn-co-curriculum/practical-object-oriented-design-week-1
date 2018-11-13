# POODR: Week 1

## Chapter 1

### 1.1 In Praise of Design

- Application design wouldn't matter if software never had to change.
- Good application design = easier to change in the future.
  - When applications are easier to change, they are more enjoyable to work on.
  - When they're harder to change, they're less enjoyable.
- Object-oriented design is about managing dependencies between objects, in a way that helps objects tolerate change.
- The difficulty of design is that your code needs to work now, AND be modifiable in the future.
  - This isn't about early optimization, which is bad programming practice. This is about using design _principles_ that are proven to make future change easier for different reasons.

> The purpose of design is to allow you to design _later..._

### 1.2 The Tools of Design

#### Design Principles

**SOLID** represents 5 of the most well known design principles:

1. Single Responsibility,
2. Open-Closed,
3. Liskov Substitution,
4. Interface Segregation, and
5. Dependency Inversion.

Other principles that will be covered later include DRY (Don't Repeat Yourself) and the Law of Demeter (LoD).

#### Design Patterns

See the Gang of Four book. This book is not about design patterns, but will go into them briefly so you know what they are and where you might use them.

### 1.3 The Act of Design

- Initially, programmers don't know very much about OOD. They can still produce a working program though.

- But even if the program is successful, a lack of design means they are hard to change, and eventually will become impossible to change.

  - > I can add that feature, but it will break everything!

- Intermediate programmers will know some OOD techniques, but not understand how to apply them. Inappropriately applied principles, overengineering, and more.

  - > I can't add that feature, because the software wasn't designed to do that.

- OOD fails when separated from the Agile feedback loop. It must be incremental in nature, no designs picked up front. Even experts can fall into this trap.

  - > I can write this, but it's not what you really want and you will eventually be sorry.

- When to design: Lots of text convincing us to use Agile.

- But it's important to note that Agile processes _guarantee change_. Using Agile practices means it's more important that good OOD principles are followed. If OOD breaks down, Agile will also break down.

- Don't use source lines of code (SLOC) to measure anything. Be careful with OOD metrics.

### 1.4 A Brief Intro to OOP

- The author covers OOP here, but we're all Ruby programmers here. Moving on.

### Notes and Motifs

We talked a lot about the differences (perceived or actual) between imperative, object-oriented, and functional design paradigms.
