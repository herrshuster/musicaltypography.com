Musical Typography
==================


Music exists because of the juxtaposition of frequencies over time. By juxtaposing notes with others, chords are formed. By juxtaposing chords over time, melodies are formed. The only two requirements for music are a set of ratios and a duration over which to express those ratios.By these two principles, every note in the audible spectrum can be defined and every time interval named.

The standard method of typographic composition maintains that type adhere to a baseline grid relative to its characters’ heights and that all different fonts adhere to a set of ratios.There exist a number of methods for generating these ratios, especially Robert Bringham’s and the Fibonacci sequence.

However, these methods are limiting. There should exist a typographic meta-ratio that allows us to express a wider range of typographic moods when composing web pages. This is what Gregory was getting at in his article. I saw the opportunity to expand the idea into an automated system. After all, the work of choosing ratios had been determined by thousands of years of musical history. Gregory’s article provided the basic calculations for my work. The idea was continued by Viljami Salminen in his blog post on musical typography. He too provided calculations that proved invaluable.

Musical typography is an idea; you are free to do with it as you please. What I sought to do is provide proof-of-concept via a usable tool.

What the musical typography tool does is generate the proper ratios for a page based on a musical key and associated quality.The key sets the root element size, where C is 100%. The root element size allows the rest of the page to be described in rems and scale when the key is changed. The quality describes the individual ratios for the H1-5 tags and the paragraph font. The paragraph is always set at 1rem as it represents the chord root. The remaining notes in the chord are distributed among the H tags. Qualities like major only have three notes and the the H1 is the largest ratio, H2 the second, and the rest are the root size. Larger qualities like domsharp9 have a full contingent of header sizes.

The key also specifies the baseline rhythm for the page. Letters sit on top of the baseline at all sizes and ratios. My musical typography tool is written in SASS/SCSS, which makes it easy to plug into your own work. 
