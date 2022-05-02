# Visual Computing Lab Official Website

## Todo

- [ ] Twtitter Page
- [ ] Add redirection to /home
- [ ] Increase width of all pages

## Contribute

### Add a new member

Adding new member is as simple as adding a new entry in yml file

#### Add Current member

- Add details of members [_data/lab_members.yml](_data/lab_members.yml). 
- Save pic in [images/teampic](images/teampic). 
- Image size must be less than 100 KB
- Image should be **square** of size (200 x 200). First crop your image to square shape then resize it to (200 x 200) size using https://www.iloveimg.com/resize-image 
- If photo is not available then use `researcher.png` placeholder image (already there).
- `url`, `linkedin` and `google_scholar` are optional
This will help in maintaining loading speed and proper alignment of website images

Sample example for adding a current member.
```yml
- name: Your Name
  photo: Your Pic
  position: You Position (Must be PhD/M. Tech/Project Assistant/Intern)
  year: 201X-Active
  url: https://sites.google.com/view/your_id
  linkedin: https://www.linkedin.com/in/your_id/
  google_scholar: https://scholar.google.com/citations?hl=en&user=your_id
```
#### Add Alumni

- Add detauks in [_data/lab_alumni.yml](_data/lab_alumni.yml)
- The `position` field accepts only values `M. Tech. (CDS)`, `Ph. D.`, `M. Tech. (research)`, `Project Assistant`, `Intern`. These are case case sensitive
- On website it will automatically show Dissertation/Thesis based on qualification.

Sample example for adding an alumnus.
```yml
- name: Aditya Kumar Pal 
  position: M. Tech. (CDS)
  year: 2018-21
  url: https://www.linkedin.com/in/adityakumarpal17059
  affiliation: Walmart Labs
  worked_on: Anomaly Detection and Localization Using Image Inpainting
```

### Add a new publication

Generate Pull request to add your publications.
Publication can be added in [_data/publications.yml](_data/publications.yml) in follwing format. 
`project_page`, `paper_link`, `code_link`, `bibtex` are optional fields
```yml
- paper: Your Paper Name
  author: List of authors 
  pub: Place where work is published
  type: Book Chapters / journal / conference (choose anyone)
  project_page: https://sites.google.com/project_link
  paper_link: https://sites.google.com/paper_link
  code_link: https://github.com/code_link
  bibtex: https://github.com/username/bibtex.tex
```

### Add news

News are stored as `.yml` file under [_data/news.yml](_data/news.yml).
An entry looks like the following:
```yaml
- date: 15 August 2021
  title: "Something great happened!"
```

### Update Slider

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
