---
title: "Thoughts on the green-eyed logic puzzle, and the importance of meta-information"
date: 2020-08-13T08:06:25+06:00
description: Thoughts on the green-eyed logic puzzle, and the importance of meta-information
menu:
  sidebar:
    name: Thoughts on the green-eyed logic puzzle, and the importance of meta-information
    identifier: sub-category
    parent: Logic
    weight: 40
hero: ted-image.jpg
mermaid: false
---

So I came across the Green-eyed logic puzzle from [Ted-ed](https://www.youtube.com/watch?v=98TQv5IAtY8) that goes:

## The problem
1. There is an island with 100 prisoners, all of who have green eyes.
2. All 100 prisoners are perfect logicians.
3. They all want to escape the island.
4. The condition of escaping the island is that one can deduce one’s own eye colour, and tell the guards the answer at midnight. If the answer is correct, the prisoner is set free. Else, he/she is killed.
5. The restrictions are: None of them knows their own eye colour (through mirrors, reflective surfaces or otherwise), and none of them is allowed to communicate with one another through any means whatsoever.
6. However, they can see each other and know everybody else’s eye colour.
You are a guest of the island owner (now called the IO). You want to free all the prisoners. The IO allows you to:

1. Make one and only one statement in the form of an announcement to all prisoners.
2. The statement does not convey any new information.

## The question
You said:

> “At least one of 100 of you has green eyes.”

At the 100th midnight, all prisoners, individually, tell the guards that he/she has green eyes and are set free.

**Why?**

## The Ted-ed solution

{{< img src="rubic-cube.jpg" title="Photo by Olav Ahrens Røtne on Unsplash" >}}

{{< vs 3 >}}

For a population of 100 prisoners, the natural response is, of course, proof by induction.

### Base case

Assuming there are only 2 prisoners, Abel & Cain. Abel knows Cain has green eyes, and vice-versa. So “at least one of you has green eyes” is not new information to any of them.

Abel thought to himself:

> Assuming I have red eyes (or any non-green colour for that matter). Then Cain will know that Cain himself has green eyes because at least one of us has green eyes. Then Cain will escape tonight. I will wait to see if it’s true.

It’s not true. Cain stays. So, by proof by contradiction, Abel knows he has green eyes and escapes on the 2nd night. So does Cain.

### Induction step

Now the problem is solved for 2 prisoners. Add a third prisoner, Seth to the pool.

Seth thought to himself:

> Assuming I have red eyes (or any non-green colour for that matter). Then Abel and Cain will ignore me and do their base case thinking. They will both escape on the 2nd night. I will wait to see if it’s true.

It’s not true. Abel and Cain stay. So, by proof by contradiction, Seth knows he has green eyes and escapes on the 3rd night. So do Abel and Cain.

Using the same logic, all 100 prisoners will escape on the 100th night.

And everybody lives happily-ever-after. Right?

---

## The lingering concern


{{< img src="concern.jpg" title="Photo by Olav Ahrens Røtne on Unsplash" >}}

{{< vs 3 >}}


After solving the problem, I thought: If all of them are perfect logicians, and the message did not convey any new information, why didn’t they just escape themselves after 100 nights (from the day they first saw each other), but must wait until the visitor makes the announcement? They sure know at least one of them has green eyes already, right?

As if a perfect logician needed somebody to remind him of something he already knew.

No, that’s not possible. So, the message “At least one you have green eyes.” must have conveyed new information. **How?**

---

## The correction
Again, let’s repeat the proof by induction.

### Base case

Now Cain and Abel first see each other. Each of them knows that the other has green eyes.

Abel thought to himself:

> Assuming I have red eyes (or any non-green colour for that matter). Then Cain will know that Cain himself has green eyes beca… wait a second. Oh Cain doesn’t know that at least one of us have green eyes. He might, if I have green eyes, but he might not.

> I’m damned.

So did Cain. They did not escape.


{{< img src="ben-shapiro.jpg" title="Abel and Cain get destroyed by Ben Shapiro’s FACT and LOGIC" >}}

{{< vs 3 >}}


**So what difference does the visitor’s message make?**

Without the message, the Abel does not know if Cain knows there is at least one green-eyed prisoner.

With the message, he does.

**Aha!**

So the message “at least one of you have green eyes” (now called Truth 0), indeed, carries the information (or meta-information) that “All of you now knows Truth 0” (now called Truth 1).

Not only that, but it also carries the meta-information that “All of you now know Truth 1” and so on.

Indeed, if you think about it hard enough, you will realise that Truth 99 is the information needed for all 100 prisoners to escape in the original problem.

Truth 1 to Truth 99, that is a whole lot of information. To call that Truth 0 “does not convey any information” is a misstatement.

---

## Afterthought

{{< img src="silence.jpg" title="Photo by Taras Chernus on Unsplash" >}}

{{< vs 3 >}}

The IO did not realise this, and neither did I, nor most of us. I have seen situations where information was disclosed to people who already have that information, because “so what, they already know this. It’s not like they will learn anything new.”

I was wrong. Repeating existing information is a form of conveying meta information. So when you think you can disclose public information, think again (or maybe think 99 more times. Maybe you will still be able to keep your island and your prisoners).