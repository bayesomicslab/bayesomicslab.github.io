---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our team includes graduate, undergraduate, and even high school researchers! Find our current lab members and alumni below.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: PI"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ms"
%}

