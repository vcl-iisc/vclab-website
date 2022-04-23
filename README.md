# Visual Computing Lab Official Website

## Todo

- [ ] Twtitter Page
- [ ] Add links/project page/code for publications
- [ ] Logo for github/webpage/linkedin for Team page
- [ ] Add redirection to /home
- [ ] Increase width of all pages

## Contribute

### Add a new member

- Save pic in [images/teampic](images/teampic). 
- Image size must be less than 100 KB
- Image should be **square** of size (200 x 200). First crop your image to square shape then resize it to (200 x 200) size using https://www.iloveimg.com/resize-image 
- If photo is not available then use `researcher.png` placeholder image (already there).
This will help in maintaining loading speed and proper alignment of website images

Add details of members in [_data/lab_alumni.yml](_data/lab_alumni.yml) or [_data/lab_members.yml](_data/lab_members.yml). 

### Add a new publication
Generate Pull request to add your publications.
Publication can be added in [_data/publications.yml](data/publications.yml) in follwing format.
```yml
- paper: Your Paper Name
  author: List of authors 
  pub: Place where work is published
  type: Book Chapters / journal / conference (choose anyone)

```

### Add news

News are stored as `.yml` file under [_data/news.yml](_data/news.yml).
An entry looks like the following:
```yaml
- date: 15 August 2021
  title: "Something great happened!"
```

### Add Slider

You can update image by going to [_layouts/homelay.html ](_layouts/homelay.html).
The slider image should be of size (640 x 360) px. Compress any image before adding to website in order to maintain loading speed.

```html
<div class="item">
  <img src="{{ site.url }}{{ site.baseurl }}/images/slider/new_image.jpg" alt="Slide 3" />
</div>
```

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

### Template Info

We use [Bootstrap](https://getbootstrap.com/) for designing the website.
Feel free to modify either the [_pages](_pages/) or the
[_layouts](_layouts/) components.

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University.

##### Template modified by [Rohit Lal](https://rohitlal.net) and Himanshu Patil
