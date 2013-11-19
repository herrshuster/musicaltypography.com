Musical Typography
==================

Musical typography is an idea; you are free to do with it as you please. What I sought to do is provide proof-of-concept via a usable tool.

What the musical typography tool does is generate the proper ratios for a page based on a musical key and associated quality.The key sets the root element size, where C is 100%. The root element size allows the rest of the page to be described in rems and scale when the key is changed. The quality describes the individual ratios for the H1-5 tags and the paragraph font. The paragraph is always set at 1rem as it represents the chord root. The remaining notes in the chord are distributed among the H tags. Qualities like major only have three notes and the the H1 is the largest ratio, H2 the second, and the rest are the root size. Larger qualities like domsharp9 have a full contingent of header sizes.

The key also specifies the baseline rhythm for the page. Letters sit on top of the baseline at all sizes and ratios. My musical typography tool is written in SASS/SCSS, which makes it easy to plug into your own work. 
