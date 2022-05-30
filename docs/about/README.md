---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /profile.jpg
head: 'Zhe Chen'
info: 'MD-Phd Candidate at Nanjing University'
interests: 'Research Interests: Computer Vision and Deep Learning.'
socials:
- title: github
  link: https://github.com/czczup
- title: email
  link: 'mailto:wztxy89[at]163.com'
actions:
- text: Projects
  link: /projects/
- text: Blog
  link: https://github.com/czczup
- text: CV
  link: /pdf/cv.pdf
footer: Made with ♥ by Fing. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

I am an MD-Phd candidate in Department of Computer Science and Technology, Nanjing University (NJU) since 2020, supervised by [Prof. Tong Lu](https://cs.nju.edu.cn/lutong/). 
I received my bachelor degree from School of Information and Electronic Engineering, Zhejiang University of Science and Technology (ZUST) in 2020.

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>