At the March 2020 [Armory Show](https://www.thearmoryshow.com), I saw a painting by [Yayoi Kusama](https://en.wikipedia.org/wiki/Yayoi_Kusama) and [was curious about the size distribution](https://twitter.com/JoshuaSchrier/status/1236394376273842176).

So I took a picture and when I got home, I wrote a bit of Mathematica code to analyze it.  I've never done any image processing before (in any language), so I relied heavily on a [blog post by Shadi Ashnai](https://blog.wolfram.com/2012/01/04/how-to-count-cells-annihilate-sailboats-and-warp-the-mona-lisa/).

Some moderate fun ensued.  I posted some of the highlights in the [twitter thread](https://twitter.com/JoshuaSchrier/status/1236394376273842176).

I suppose that armed with empirical distribution of radii, the total circle density, and the knowledge that they're mostly uniformly distributed across the surface (except for some anomalies near the bottom)...one could in principle generate generate these programmatically...


As far as I know, nobody has previously performed a statistical analysis of her paintings, comparable to some of the quantitative analyses that have been done on paintings and drawings in  general by [Kim et al (2015)](https://doi.org/10.1038/srep07370); [Sigaki et al (2018)](https://doi.org/10.1073/pnas.1800083115) perspective by [Ornes (2015)](https://doi.org/10.1073/pnas.1504488112), fractal analysis of Jackson Pollock's drip paints by [Taylor et al. (1999)[https://doi.org/10.1038/20833], entropy-based analyses of M. C. Escher's art by [Lopes and Machado (2019)](https://doi.org/10.3390/e21060553), and brushstroke analysis of van Gogh by [Johnson et al. (2008)](https://doi.org/10.1109/MSP.2008.923513).  This might be especially interesting in the case of Kusama, as she self-reports painting as therapeutic for anxiety issues; there is some literature on the use of mathematical morphology and image segmentatino to automate the psychological interpreation of drawings by color analysis by [Kato and Kimoto (2015)](https://doi.org/10.14738/aivp.34.1316).

 
