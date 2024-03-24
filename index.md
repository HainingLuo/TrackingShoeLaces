---
layout: academic
author: Haining Luo, Yiannis Demiris
affiliation: Personal Robotics Lab, Imperial College London
site.project-affiliation.url: www.google.com
site.show_github: false
---

**Abstract**: Robot Shoe Lacing is a challenging manipulation task due to the deformation of the shoelace and the resulting intricate shoelace structures. Existing methods for tracking Deformable Linear Objects are primarily demonstrated on relatively simple tasks involving objects with simple geometries. In this work, we explore different approaches to shoelace tracking and propose the Tracking Shoelaces algorithm which combines probabilistic registration with Digital Twins. One of the key requirements for tracking in Shoe Lacing is to maintain the relation between the shoelace and the eyelets. Leveraging the Digital Twins, our algorithm reliably identifies collisions and prevents the shoelace from escaping the eyelets, thereby preserving the topological structure of the shoelace. The performance of the proposed algorithm is compared against popular Deformable Linear Object tracking algorithms with real robot data, simulated data and human demonstration data. Our experiments show that our algorithm consistently preserves the shoelace-eyelet relation across all scenarios.


# Experiments

We test the performance of our proposed TSL with CDCPD2, anchored CDCPD2 and GLTP with simulated data, human demonstration and physical robot data.
<center>
  <video poster="assets/material/TSL_IROS_1min_cover.png" autoplay controls muted loop width="720">
    <source src="assets/material/TSL_IROS_1min_narrated.mp4" type="video/mp4">
  </video>
</center>


<!-- ## Simulated data -->

<!-- ![TslSimUnity](/home/haining/Projects/webpages/TrackingShoeLaces/material/experiment%20slides_hand_unity_3s.mov) -->
<!-- ![TslSimUnity](/assets/material/sim.mp4) -->

<!-- <video poster="assets/material/image0.jpg" autoplay controls muted loop width="640">
  <source src="assets/material/sim.mp4" type="video/mp4">
</video> -->

<!-- ## Human demonstration -->

<!-- ## Physical robot data -->


<!-- [Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project. -->

<!-- ```js
> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
``` -->


<!-- 
##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->
