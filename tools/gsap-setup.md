## GSAP SETUP

# Using as CDN link
1. Put this shit in your html's head tag
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>

2. yOU fkin good to go mate.

# Using locally REQUIRES npm
0. if you already have npm, SKIP to 2
1. visit node-setup.md
2. install gsap: npm install gsap
3. use gsap in js file: 
- import { gsap } from "gsap";
- gsap.to(".box", { duration: 1, x: 100 });
