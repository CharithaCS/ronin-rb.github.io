---
layout: page
title: Install - OpenSUSE
---

# Installing Ronin on OpenSUSE

## Copy/Paste Instructions

```shell
sudo zypper -n in -l gcc make ruby-devel readline-devel sqlite3-devel
sudo gem install ronin
```

## Detailed Breakdown

{% include install/gcc_and_make.md %}

```shell
sudo zypper -n in -l gcc make
```

{% include install/ruby.md %}

```shell
sudo zypper -n in -l ruby-devel
```

{% include install/c_libraries.md %}

```shell
sudo zypper -n in -l readline-devel sqlite3-devel
```

{% include install/ronin.md %}

{% include install/post_install.md %}

{% include install/troubleshooting.md %}
