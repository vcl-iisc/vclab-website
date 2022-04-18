[![Netlify Status](https://api.netlify.com/api/v1/badges/dcf3d5d0-a4a4-486f-bd9a-64b612392aad/deploy-status)](https://app.netlify.com/sites/brave-bell-c85a34/deploys)

## Todo
- [ ] Replace image by its compressed counterparts
- [ ] Update Team members name
- [ ] Change Netlify build
- [ ] Add Publication
- [ ] Change news section

## Setup

### For Mac/Linux

``` bash
brew install ruby
gem install bundler jekyll
```

### For windows Install 
- Download Ruby+Devkit 2.6.9-1 [Link to Download](https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.9-1/rubyinstaller-devkit-2.6.9-1-x64.exe)
  
Clone this repository, then install the dependencies:


``` bash
bundle install
```

## Run

Run the local webserver with:

``` bash
bundle exec jekyll serve
```

## Contribute

### Add a new member
- Save pic in [images/teampic](images/teampic). Image size must be less than 200 KB and should be square to maintain loading speed and proper alignment of website images
- Add details of members in [_data/lab_alumni.yml](_data/lab_alumni.yml) or [_data/lab_members.yml](_data/lab_members.yml). 

### Add a new publication

Publications are stored as `.json` file under
[_data/publications.json](_data/publications.json).
This json file is exported from [Zotero](https://www.zotero.org/)
bibliography tool.

Just add a new entry to the list like this:

``` json
{
  "id": "http://zotero.org/groups/2386072/items/NU9LTX7C",
  "type": "article-journal",
  "title": "Foo",
  "container-title": "IEEE Transactions on Medical Imaging",
  "page": "448-459",
  "volume": "38",
  "issue": "2",
  "source": "IEEE Xplore",
  "abstract": "Bar",
  "DOI": "10.1109/TMI.2018.2865709",
  "author": [
    {
      "family": "",
      "given": ""
    },
  ],
  "issued": {
    "date-parts": [
      [
        "2019",
        2
      ]
    ]
  }
}
```

### Add news

News are stored as `.yml` file under [_data/news.yml](_data/news.yml).

An entry looks like the following:

```yaml
- date: 03/09/19
  title: "Something great"
  tags:
    - some
    - tags
  content: Lorem ipsum dolor sit amet, consectetur adipiscing elit,
    sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    Eu turpis egestas pretium aenean. Luctus venenatis lectus magna fringilla
    urna porttitor. Lorem ipsum dolor sit amet. Pellentesque massa placerat
    duis ultricies. Commodo viverra maecenas accumsan lacus vel.
```

### Edit template

We use [Bootstrap](https://getbootstrap.com/) for designing the website.
Feel free to modify either the [_pages](_pages/) or the
[_layouts](_layouts/) components.

# VCLab website template

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University.
##### Template was modified by Rohit Lal and Himanshu Patil