# Zola Resume

from [template](https://github.com/alongwy/zola-resume) that has been redesigned form [hugo resume](https://github.com/eddiewebb/hugo-resume).

## Features
+ This is basically a single-page website with auto-scrolling based on left-hand nav.
+ Dedicated project/publications pages allow more detail.
+ Includes a client-side search at '/search'. 
+ Includes an `/admin` endpoint that can allow authorized users to use a WYSIWYG editor and commit files back to markdown, but with a Wordpress/CMS like experience.

## Quick Start

```bash
git clone git@github.com:annefou/annefou.github.io.git
cd annefou.github.io
zola serve
# open http://127.0.0.1:1111/
```

### Summary
Edit the main `contents/_index.md with a brief bio/summary`

### Data files
Data files are used for simple content presented on the homepage.

- [data/certifications.json](https://github.com/AlongWY/zola-resume/blob/main/data/certifications.json)
- [data/social.json](https://github.com/AlongWY/zola-resume/blob/main/data/social.json)
- [data/skills.json](https://github.com/AlongWY/zola-resume/blob/main/data/skills.json)
- [data/experience.json](https://github.com/AlongWY/zola-resume/blob/main/data/experience.json)
- [data/education.json](https://github.com/AlongWY/zola-resume/blob/main/data/education.json)

### Projects/Opensource

The difference indicates your role as originator or colaborator.

### Publications
Similar to projects, create them under `publications`. Include any papers, speaking engagements, articles, etc.

### Blog / Posts
Similar to posts, create them under `blog`. Include any thoughts, musiings, etc.
**This template does not support a `posts` folder**

## Credits

This project uses the Hugo Resume theme that was modified and ported by Feng Yunlong to support zola.

