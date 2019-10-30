---
title: What next? # The title of the page
date: 0000-01-03  # Page order is set by date
---

Add a social badge by adding/modifying the following to your markdown:

```
{% raw %}{% include profile.html
  display_name="Nick Bourdakos"
  profile_photo="https://path.to/a/photo/of/you.jpg"
  twitter_username="bourdakos1"
  medium_username="bourdakos1"
  github_username="bourdakos1"
  linkedin_username="nicholasbourdakos"
%}{% endraw %}
```

> **Note:** Leaving out a username will remove the icon from the profile.

{% include profile.html
  display_name="Nick Bourdakos"
  profile_photo="https://pbs.twimg.com/profile_images/1035328157707128832/e_0EXqIu.jpg"
  twitter_username="bourdakos1"
  medium_username="bourdakos1"
  github_username="bourdakos1"
  linkedin_username="nicholasbourdakos"
%}

{% include profile.html
  display_name="nigel"
  profile_photo="https://pbs.twimg.com/profile_images/1011641648864952322/mVZldhNK_400x400.jpg"
  github_username="pnbrown"
  linkedin_username="pnigelbrown"
%}

{% include profile.html
  display_name="Pooja Mistry"
  profile_photo="https://pbs.twimg.com/profile_images/1121507773597011982/-EjvIm6J_400x400.png"
  twitter_username="poojamakes"
  medium_username="poojamakes"
  github_username="pmmistry"
  linkedin_username="pmmistry"
%}
