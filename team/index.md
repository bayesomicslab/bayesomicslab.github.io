---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our team includes graduate, undergraduate, and even high school researchers! Find our current lab members and alumni below.

{% include section.html %}

# Current

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc; group:"current""
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: masters"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: highschool"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: dog"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: cat"
%}

# Alumni

{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: masters"
%}
{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: highschool"
%}
{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: dog"
%}
{%
  include list.html
  data="members"
  group="alum"
  component="portrait"
  filters="role: cat"
%}
