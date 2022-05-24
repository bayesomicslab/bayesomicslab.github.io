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
  filters="role: postdoc; group:current"
%}
{%
  include list.html
  group="current"
  component="portrait"
  filters="role: phd; group:current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters; group:current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad; group:current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: highschool; group:current"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: dog; group:current"
%}
{%
  include list.html
  data="members"
  group="current"
  component="portrait"
  filters="role: cat; group:current"
%}

# Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc; group:alum"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd; group:alum"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters; group:alum"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad; group:alum"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: highschool; group:alum"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: dog; group:alum"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: cat; group:alum"
%}
