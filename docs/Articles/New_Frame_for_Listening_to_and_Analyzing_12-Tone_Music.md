---
layout: default
title: New Frame for Listening to and Analyzing 12-Tone Music
nav_order: 6
parent: Articles
---
# New Frame for Listening to and Analyzing 12-Tone Music

*Author(s):* Alec Hopkins

*Editors(s):* 

*Date:* 2025-02-18

> A new way of listening to 12-tone music, striving to make it more accessible to the average listener

In the early 20th century, a German composer named Arnold Schoenberg was beginning to explore the realms beyond tonality. He believed a departure from the tonal system was the next logical step from the increasingly chromatic music of the romantic period. At what point was returning to a tonal center merely obligatory? Why not let dissonance take center stage and be the focus of a composer’s life?

At the turn of the century, Schoenberg dove headfirst into the unknown territories of atonal music. Upon debut, people and critics did not find his music appealing. However, his contemporaries, like Igor Stravinsky, were supportive of this bold departure. Schoenberg never touched tonality again.

Despite this drastic departure, he still viewed himself as an heir to the rich tradition of Western Art music. He incorporated elements of form and motivic development to bring structure to the chaos. As time went on, he began to realize that composing atonal music in this hyper-romantic style was challenging, and that he did not have a system, like tonality or functional harmony, that could help him create ideas within. So, he decided to invent one himself. This is where the 12-tone system enters.


## The 12-Tone System

Unlike what some people may think, the 12-tone system is not a genre, it’s a system used for atonal compositions. We wouldn’t call the genre of Beethoven’s 5th Symphony C minor, it’s a Symphony composed in the key of C minor. 

To use the 12-tone system, a composer crafts a tone row, made up of all 12 chromatic pitches in a specific order. That order can be inverted, reversed or both starting on any pitch, as long as the interval between the notes stays the same. All of these variations can be placed in a matrix for visual reference, Here is one as an example, with P0 being the prime or original tone row.

! Insert the image here

Composers will then organize their musical ideas around these different variations of the rows. Each row must be used in its completion, but multiple rows can be used at the same time, and even cross voices with each other. As long as a piece uses this method, it can be classified as a 12-tone composition.

Shoenberg seemed to have struck gold with this method, as its popularity and use became widespread among 20th century composers. He had students such as Anton Webern and Alban Berg who adopted the 12 tone system, but used it in strikingly different ways than their mentor. Webern, especially, would meticulously craft his tone rows to be full of symmetries and patterns. Obsessed with finding those perfect rows, in his mind.

## The Listening Experience
As you can imagine, the experience of listening to a 12-tone composition is . . . different, to say the least. It is unlike anything you have ever heard, or will ever hear. Without any previous knowledge, it would be understandable if someone believed that these compositions were purely random. That is not the case but due to the nature of the system, the tone rows end up getting lost, losing the trees through the forest.

Here are a few examples to listen to:

<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/watch?v=bQHR_Z8XVvI" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>
<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/watch?v=kn3FqCK0wWw" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>
<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/watch?v=8PDcD3PoYA4" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>

## TTSpat - Twelve Tone Spatializer
While learning about Schoenberg and the 12-tone system again in a music history class, I had the idea of using space to help 12-tone compositions be more accessible to listeners, allowing the patterns and symmetry to present themselves in a way that could be heard, not just seen after doing vigorous score analysis.

Dr. Kevin Anthony helped me put together a program in MAX 9 that would accomplish this. The program takes midi input, either live or a midi file, then outputs the 12 different chromatic pitches to 12 different channels. Those channels are then arranged in a clock shape using the advanced sound system in BYU’s Box Theatre, allowing each pitch to hold its own position in the room.

We recently did a demo of the program (February 7th, 2025) with a mixed degree of success. For the demo, we played a piece by Webern and a composition I wrote for the program. The left speakers weren’t working properly, so it was harder to hear the patterns than I initially realized. However, they were still there to an extent. Further research and testing are still needed to assess whether or not spatializing the 12 tones will produce the desired outcome.

## Limitations and Future Developments
The program is very rudimentary, and has many limitations, all of which will hopefully be overcome with more time and testing. 

The biggest limitation is the quality of the playback, which is severely limited by MAX right now. As the program currently stands, it is limited to outputting playback using only simple waveforms built into MAX (sine waves, saw waves, square waves, and triangle waves). If we could engineer the program to output samples from a virtual machine as a performance, that would expand the ability of performances. (This is a priority first for piano compositions, then other instruments can follow).

The second limitation is the clock-like setup. Right now, each pitch only has one place in space, no matter the octave. This might limit the ability of listeners to perceive the tone rows due to overlapping octaves. One possible solution would be to change the distance for each octave, but we have yet to find a simple solution to this that doesn’t involve brute-forcing each individual pitch to its own channel.

If these limitations can be overcome, I believe this could become a valuable tool to help 12-tone music become more accessible to listeners.

[Example link to edit later](https://musictheory.pugetsound.edu/mt21c/TwelveToneTechnique.html "Example Link to Edit Later")