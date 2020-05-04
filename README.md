# news-and-alerts-section
Getting information to the end user is often a top priority for many organizations. With a dedicated News & Alerts sectional, you can feature this information so that all parties are kept up-to-date.

## Tutorial
For detailed instruction's, view Solodev's [How To Add a News and Alerts Section to Your Website](http://www.solodev.com/blog/web-design/how-to-add-a-news-and-alerts-section-to-your-website.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/xq6g2ha5/).

## HTML
The tutorial contains the following basic HTML markup.

```
<section class="section section--background section--news mt-5 mb-5">
  <div class="container">
    <div class="row">

      <!-- News Section -->
      <div class="col-lg-6 col-12">
        <h2 class="h1 mt-xl-n1 mb-4 mb-md-5 pb-2">News</h2>

        <div class="box-news">
          <a aria-label="LunarXP Wins Space Innovator of the Year Award" href="#">
            <div class="row">
              <div class="col-lg-3 col-4 pr-1">
                <img alt="LunarXP Wins Space Innovator of the Year Award" class="img-fluid" src="images/news-1.jpg">
              </div>
              <div class="col-lg-9 col-8">
                <h2>LunarXP Wins Space Innovator of the Year Award</h2>
                <p>April 24, 2020</p>
              </div>
            </div>
          </a>
        </div>

        <div class="box-news">
          <a aria-label="New Spending Bill Expands Funding for Space Exploration" href="#">
            <div class="row">
              <div class="col-lg-3 col-4 pr-1">
                <img alt="New Spending Bill Expands Funding for Space Exploration News Image" class="img-fluid" src="images/news-2.jpg">
              </div>
              <div class="col-lg-9 col-8">
                <h2>New Spending Bill Expands Funding for Space Exploration</h2>
                <p>April 6, 2020 2:35 pm</p>
              </div>
            </div>
          </a>
        </div>

        <div class="box-news">
          <a aria-label="LunarXP Sets Target for First Mars Landing in 2030" href="#">
            <div class="row">
              <div class="col-lg-3 col-4 pr-1">
                <img alt="LunarXP Sets Target for First Mars Landing in 2030 News Image" class="img-fluid" src="images/news-3.jpg">
              </div>
              <div class="col-lg-9 col-8">
                <h2>LunarXP Sets Target for First Mars Landing in 2030</h2>
                <p>March 20, 2020</p>
              </div>
            </div>
          </a>
        </div>

        <div class="col-lg-9 offset-lg-3 col-md-8 offset-md-4 col-7 offset-4">
          <a href="#" class="view">View All</a>
        </div>
      </div>

      <!-- End of News Section -->

      <!-- Alerts Section -->
      <div class="col-lg-6 col-12 pr-xl-0 mt-5 mt-lg-0">
        <h2 class="h1 mt-xl-n1 mb-4 mb-md-5 pb-2">Alerts</h2>

        <div class="box-news box-news--alerts">
          <a aria-label="Astronaut Leadership Training Canceled" href="#">
            <div class="row">
              <div class="col-lg-2 col-4 pl-xl-4">
                <img src="images/alert-image.png" class="img-fluid" alt="Astronaut Leadership Training Canceled">
              </div>
              <div class="col-lg-9 col-8 pl-xl-4 pr-xl-0">
                <h2>Astronaut Leadership Training Canceled</h2>
                <p>April 20, 2020 2:46 pm</p>
              </div>
            </div>
          </a>
        </div>

        <div class="box-news box-news--alerts">
          <a aria-label="Habitat Offerings to Include New Hydroponics Lab" href="#">
            <div class="row">
              <div class="col-lg-2 col-4 pl-xl-4">
                <img src="images/alert-image.png" class="img-fluid" alt="Habitat Offerings to Include New Hydroponics Lab">
              </div>
              <div class="col-lg-9 col-8 pl-xl-4 pr-xl-0">
                <h2>Habitat Offerings to Include New Hydroponics Lab</h2>
                <p>March 20, 2020 2:45 pm</p>
              </div>
            </div>
          </a>
        </div>

        <div class="box-news box-news--alerts">
          <a aria-label="Lunar XPlorer transportation Delays" href="#">
            <div class="row">
              <div class="col-lg-2 col-4 pl-xl-4">
                <img src="images/alert-image.png" class="img-fluid" alt="NLunar XPlorer transportation Delays">
              </div>
              <div class="col-lg-9 col-8 pl-xl-4 pr-xl-0">
                <h2>Lunar XPlorer transportation Delays</h2>
                <p>February 20, 2020 2:44 pm</p>
              </div>
            </div>
          </a>
        </div>

        <div class="col-lg-10 offset-lg-2 col-md-8 offset-md-4 col-7 offset-4">
          <a href="#" class="view">View All</a>
        </div>
      </div>
      <!-- End of Alerts Section -->
    </div>
  </div>
</section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```