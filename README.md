what do i know? let's see...

- js/ts/tsx/tsx
- web tech: canvas api, web audio api, webgpu, anything that can be found on mdn really
- html + css (NO taliwind - i've never used taliwind before, i just opt for svelte sfc instead)
- preact/svelte/vue
- java/c#
- deno (i do know nodejs but i prefer deno tbh)
- webgpu (i really love webgpu, it is actually easier than opengl for some reason i just can't tell tbh)
- there are other things that i know but i can't recall. i wouldn't say "c/c++" here because i don't trust my c code

but honestly, i think it doesn't matter if i know a lot of technologies or not. most of the time i just read the docs and figure out the solution. sometimes i have to go through small tutorial to get started with framework or language, but after that i read the docs anyways.

my eventual goal is to become the "stage engineer" (as in controlling lights, video walls and stuffs on liveshows idk it's just way too cool)

paid softwares are kinda expensive, and so i've been trying to make a clone of them (well, except for windows, but i would say windows came with my laptop). adobe after effect? no thanks, i'll make my own motion graphics editor (in fact, [i got the prototype version of motion graphics editor working \[1\]][1], but right now i am reconsidering entire architecture of the app). digital audio workspace? i've made mixery ([\[2\]][2], [\[3\]][3]) before, though the 2nd version is kind of unfinished (and i don't think i'll come back to it, as i lost my interest in electronic music).

right now i am focusing on apps that can be used for live performance/liveshows, since im really into it. however, i quickly found out that the equipments to make a "mini-stage" are really expensive. maybe i can repurpose the living room TV as video panel, but what's about light fixtures?

but anyways, i've came up with ideas and i am willing to share them to whoever reading this:

- live compositing: it's kinda like blender's compositor or blackmagicdesign's fusion, but you would control it in real time, like live color correction or live keying. i am planning to use webgpu for this.
- motion graphics editor: i wouldn't say "basically after effect" because i don't plan on doing 3d (because if you want 3d, you have blender or fusion anyways), but it would be a steping stone for me to cook some 2d animations. i've seen some animated music videos and they are really cool, so i basically want to do that lmao.
- painting app: for this one, i want to keep it simple with nice UX on mobile devices. on desktop, you likely want to use krita anyways. painting app can be used alongside live compositing and motion graphics to paint the masks (or mattes? im not sure).
- pipeline management: a simple app for managing assets authoring pipeline really. the idea is that output of one program becomes input of others, and pipeline management would automatically export and import the files upon saving. also if possible, i would like to make it update in real time.
- _TODO_

all of the above will be managed in [Nahara-OSS][4] organization.

[1]: https://github.com/Nahara-OSS/motion
[2]: https://github.com/nahkd123/Mixery
[3]: https://github.com/Mixery-OSS/Mixery
[4]: https://github.com/Nahara-OSS
