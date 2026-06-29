# Daily Learning
## Morning Planning
![Mona the Octocat](https://octodex.github.com/images/original.png)
## Review
1. Step 1
1. Step 2
1. Step 3
- [x] This task is complete
- [ ] This task is not complete
      
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
