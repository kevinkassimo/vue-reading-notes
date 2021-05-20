# Vue Reading Notes

This is my own notes of reading the `vue-next` (Vue 3.0) source code. I am a React user and has never used Vue before, so I think it would be interesting to read through its source code while going through its docs and guide (especially that my understanding of virtual DOM is really hand-wavy).

Since the notes is only for my own benefit, it will be pretty disorganized, as I document fun things I find along the way.

The source code I am reading is a snapshot taken at `f7c54caeb1dac69a26b79c98409e9633a7fe4bd3` on May 19, 2021. Most recent version number is `3.1.0-beta.3`. This notes is written using Typora for easier reading, and it might use a dialect of Markdown.

### Entry

+ `Vue.createApp` is from `runtime-dom` pkg.