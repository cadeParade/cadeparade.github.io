---
layout: post
title: Public Work
---

<div class="p-centered">
  Below, please find a few examples of public-facing work I've done. 
  <br>  
  <a href="#percy-visual-engine-overview">Percy Visual Engine Overview</a>
  <br>
  <a href="#embermap-videos">EmberMap Videos</a>

  <div id="percy-visual-engine-overview" class="section">
    <h3>Percy Visual Engine Overview</h3>
    <iframe width="576" height="315" src="https://www.youtube.com/embed/9X-1BToA2Iw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen class="youtube-embed"></iframe>
    <p class="video-caption">In this <a href="https://www.browserstack.com/webinars/percy-visual-engine-pt">webinar</a> I cover the new (at the time) changes to the Percy visual diffing algorithm. As the main and sole developer on this project, I planned, developed, shipped, and iterated on all the features covered in this talk. I also designed the content and slides for this talk.</p>
  </div>

  <div class="divided"></div>

  <div id="embermap-videos" class="section">
    <h3>EmberMap Videos</h3>
    <p>For each of these videos (and series), I came up with the idea for the content based on projects I was currently working on, planned the overall "story" of the content, took audio and screen recording, and wrote up the walk-through summaries below the videos on the EmberMap site.</p>
    <div class="p-left-aligned">
      <div class="video-block">
        <a href="https://embermap.com/topics/tracking-arrays">Tracking Arrays Series (4 videos)
          <br>
          <img src="https://embermap.imgix.net/public/images/c1c05140-de0f-466a-8dfc-69ea55315818/Arrays.png?auto=format%2Ccompression&amp;dpr=2&amp;w=560">
        </a>
        <p class="video-caption">EmberJS framework extends the native JS `array` prototype to include lots of useful stuff. But if you don't know it's there, it can be confusing to understand what's happening. This is relevant when you're using tracked properties in Ember, when the tracked property is an array. When is it auto-updated? When isn't it? How can you ensure your app behaves the way you expect? This series covers all of this.</p>
      </div>
      <div class="video-block">
        <a href="https://embermap.com/topics/converting-to-octane-first-look">Converting to Octane: First Look Series (4 videos)
          <br>
          <img src="https://embermap.imgix.net/public/images/903b1671-738b-43d6-b7b5-40a79b6d23dd/series-poster.png?auto=format%2Ccompression&amp;dpr=2&amp;w=560">
        </a>
        <p class="video-caption">When EmberJS released their Octane edition, sweeping changes needed to be made to existing apps to work with the new paradigms. This video series explains the underlying reasoning behind the changes and how to complete the conversions for two tasks that were paradigm-shifts from previous versions -- Converting files to use native JS class syntax and converting components to use Glimmer.</p>
      </div>

      <div class="video-block">
        <a href="https://embermap.com/video/accessing-metadata-from-ember-data-s-findrecord-method">Accessing Metadata from Ember Data's `findRecord` Method</a>
        <br>
        <video controls width="100%" poster="https://embermap.imgix.net/public/images/25919378-6c1a-498a-bc12-865cc32f3b70/poster.png?auto=format%2Ccompression&dpr=2&w=560">
          <source src="https://d19c50bha6zcb3.cloudfront.net/encodes/1130-e0f63f4b-bf6d-4f63-8c8f-22e1201bff1d.mp4" type="video/mp4" >
        </video>
        <p class="video-caption">Sometimes you need to retrieve some metadata from an API response returning a single item. Seems straightforward, but there is actually no built-in way to do this with ember-data. This video shows you how.</p>
      </div>

      <div class="video-block">
        <a href="https://embermap.com/video/testing-loading-states">Testing loading states</a>
        <video controls width="100%" poster="https://embermap.imgix.net/public/images/1f3851eb-c45d-42d7-982c-2b941bebb275/Frame-1.png?auto=format%2Ccompression&dpr=2&w=560">
            <source src="https://d19c50bha6zcb3.cloudfront.net/encodes/1085-20711769-3e45-4680-ae94-346ed7ef16b8.mp4" type="video/mp4">
        </video>
        <p class="video-caption">Loading states are important indicators for your users, but can be difficult to check in automated tests. In Ember, acceptance tests automatically wait for all pending requests to finish before moving to the next line, making it hard to look at an interim state. This video shows how we can pause acceptance tests in the middle of a network request to make sure everything looks good during the crucial loading state.</p>
      </div>
    
  

    </div>
  </div>
  

</div>
