# bootstrap-all
general Working repot - Learning and creating templates with Bootstrap the CSS framework



## Define the grid
- Documentation: [https://getbootstrap.com/docs/5.1/layout/grid/](https://getbootstrap.com/docs/5.1/layout/grid/)


## Footer 
```
<!-- Footer -->
    <footer id="footer" class="pb-4 pt-4 bg-dark">
      <div class="container">
        <div class="row text-center">

            <div class="col-12 col-lg"><a href="#">FAQ</a></div>
            <div class="col-12 col-lg"><a href="#">Repositories</a></div>
            <div class="col-12 col-lg"><a href="#">Languages</a></div>
            <div class="col-12 col-lg"><a href="#">Projects</a></div>
            <div class="col-12 col-lg"><a href="#">Snippets</a></div>
            <div class="col-12 col-lg"><a href="#">Contact</a></div>

        </div>

      </div>
    </footer>
```

## header - Navbar
- Documentation at [https://getbootstrap.com/docs/5.1/components/navbar/](https://getbootstrap.com/docs/5.1/components/navbar/)

## Carousel
- Documentation at [https://getbootstrap.com/docs/5.1/components/carousel/](https://getbootstrap.com/docs/5.1/components/carousel/)


### Informative Text into de Carousel (Adding Buttons to Carousel)

- Example Code here: 
```
<!-- Main -->
<main id="main">
  <div id="carousel" class="carousel slide carousel-fade" data-bs-ride="carousel" data-pause="false">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./img/k1_2.jpg" class="d-block w-100" alt="Code 1">
      </div>
      <div class="carousel-item">
        <img src="./img/k2_2.jpg" class="d-block w-100" alt="Code 2">
      </div>
      <div class="carousel-item">
        <img src="./img/k3_2.jpg" class="d-block w-100" alt="Code 3">
      </div>
    </div>
    <div class="overlay">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-6 offset-md-6 text-right">
            <h1>Template Bootstrap Cool</h1>
            <p class="d-none d-md-block">Template Bootstrap Cool this is a really nice detail!.</p>
            <a class="btn btn-outline-info" href="#">I want to become a supporter</a>
            <button type="button" class="btn btn-warning">Buy Images</button>
            <button type="button" class="btn btn-special" data-bs-toggle="modal" data-bs-target="#modalCompra">Buy Products</button>
          </div>
        </div>
      </div>
    </div>

  </div>
</main>
```


## Adding Cards
- Documentation at [https://getbootstrap.com/docs/5.1/components/card/](https://getbootstrap.com/docs/5.1/components/card/)
- Different type od Styles [https://getbootstrap.com/docs/5.1/components/card/#card-styles](https://getbootstrap.com/docs/5.1/components/card/#card-styles)

### Adding Badges (tags)
- Documentation at [https://getbootstrap.com/docs/5.1/components/badge/](https://getbootstrap.com/docs/5.1/components/badge/)


## Adding a fluid container (full width container)
- Documentation at [https://getbootstrap.com/docs/5.1/layout/containers/#fluid-containers](https://getbootstrap.com/docs/5.1/layout/containers/#fluid-containers)

## Forms
- Documentation at [https://getbootstrap.com/docs/5.1/forms/layout/](https://getbootstrap.com/docs/5.1/forms/layout/)
- Password inputs: [https://getbootstrap.com/docs/5.1/forms/overview/](https://getbootstrap.com/docs/5.1/forms/overview/)
- Buttons documentation: [https://getbootstrap.com/docs/5.1/components/buttons/](https://getbootstrap.com/docs/5.1/components/buttons/)


### Form validations
- Documentation at: [https://getbootstrap.com/docs/5.1/forms/validation/](https://getbootstrap.com/docs/5.1/forms/validation/).


## Tooltips (abbr and tooltips)
- Documentation at [https://getbootstrap.com/docs/5.1/content/typography/#abbreviations](https://getbootstrap.com/docs/5.1/content/typography/#abbreviations)
- Tooltips: [https://getbootstrap.com/docs/5.1/components/tooltips/](https://getbootstrap.com/docs/5.1/components/tooltips/)

## Scrollspy
- Doc at: [https://getbootstrap.com/docs/5.1/components/scrollspy/](https://getbootstrap.com/docs/5.1/components/scrollspy/)

<body data-bs-spy="scroll" data-bs-target="#navbarSupportedContent">



## Modals
- Documentation at: [https://getbootstrap.com/docs/5.1/components/modal/](https://getbootstrap.com/docs/5.1/components/modal/). 
- Documentation at: https://getbootstrap.com/docs/5.1/components/modal/
- Los modals can be located at the same level thatn the body tag. (at the end of the file, below the footer)
- Form validations: https://getbootstrap.com/docs/5.1/forms/validation/#supported-elements 
- The class `was-validated` should be applied to the `form` tag.
- Must combine modals and forms itself


### Documentation of this template
- The code was created using Bootstrap v5.1
- Completely responsive, tested in Chrome and Firefox latest Browser versions on Jan 2022.
- Different id's are:
  - header
  - main
  - speakers
  - place-time
  - place-time2
  - form-here
  - footer
