# Tool Learning Log

## Tool: Bootsrap

---

### 3/16/25:
Things you tried, progress you made, etc.

Tried-
Implemented Bootstrap's grid system for responsive layouts.
Experimented with various button styles and sizes.
Integrated cards for displaying content blocks.
Implemented components such as dropdown and Modal.

Progress-
Gained a better understanding of Bootstrap's utility classes for spacing, typography, and colors.
Successfully created basic responsive layouts that adapt to different screen sizes..
Improved consistency of web page design. Before i was struggling with the compent modal, but after few youtube videos about it, it helped me fix my code and complete my assignment. 

Ex;
```
<div class="card invincible-card mb-4">
                    <div class="card-header">
                      Omni-Man(Nolan Grayson)
                    </div>
                    <div class="card-body text-center">
                        <img src="Omni-ussy.jpg" alt="Atom Eve" class="img-fluid character-image">
                        <p>Nolan Grayson, Mark's father.</p>
                        <button class="btn invincible-button" data-bs-toggle="modal" data-bs-target="#nolanModal">Learn More</button>
                    </div>
                </div>
```
  In this example is shown a Omni-man modal window(pop-up). I often had struggles with it not popping up at all.

Challenges-
Overriding Bootstrap's default styles to achieve custom designs without breaking responsivenes.
Understanding the nuances of the grid system, especially when dealing with complex layouts.
Making sure the components are accessible.

A-ha moments-
Realized the power of utility classes for rapid styling and layout adjustments.
Discovered how effectively Bootstrap's grid system simplifies responsive design.
Understood the importance of carefully reading the Bootstrap documentation to avoid common diffcultiess.


Questions you still have-
How to effectively customize Bootstrap's components for complex UI designs while maintaining responsiveness?
How to handle accessibility considerations when using Bootstrap components?

What you're going to try next-
Explore Bootstrap's theming capabilities to create custom design systems.
Focus on improving accessibility of pages created with Bootstrap.
 Youtube links used-
 https://www.youtube.com/watch?v=kdHWt2S3HFw
 https://www.youtube.com/watch?v=jp_p6wCkc9I



### 3/30/25:
Tried:
Bootstrap's grid system for responsive layouts.
Integrated Bootstrap's carousel component for image gallery.
Utilized Bootstrap's utility classes for styling and spacing.
Used Bootstrap's navbar component.

Progress:
Improved the responsiveness of the website, ensuring it adapts to different screen sizes.
Successfully implemented a dynamic image gallery using the Bootstrap carousel.
Enhanced the visual presentation of the website using Bootstrap's styling capabilities.
Improved the website's navigation.
I have learned to use icons, and implement them into my html.
```
<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="./img/balloon-1.jpg" class="d-block w-100" alt="Image 1">
        </div>
        <div class="carousel-item">
            <img src="./img/balloon-2.jpg" class="d-block w-100" alt="Image 2">
        </div>
        <div class="carousel-item">
            <img src="./img/balloon-3.jpg" class="d-block w-100" alt="Image 3">
        </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
    </button>
</div>
```
This snippet demonstrates the implementation of a Bootstrap carousel. The carousel class initiates the carousel functionality, and the carousel-item classes contain the images. The carousel-control-prev and carousel-control-next buttons allow users to navigate through the images. This component was easy to implement, and allowed for the gallery to be very clean and efficient.

Challenges:
Customizing Bootstrap's default styles to match the desired aesthetic.
Understanding the proper use of the bootstrap components.

A-ha moments:
Realized the efficiency of Bootstrap's utility classes for rapid styling.
Discovered the power of the Bootstrap grid system for creating responsive layouts.
Understood how bootstrap components such as the navbar and carousel simplify web development.

Questions you still have:
What are the best practices for customizing Bootstrap's components for complex designs?
How to handle complex layouts with bootstrap that include many different components.

What you're going to try next:
Explore Bootstrap's theming capabilities to create a custom design system.
Investigate advanced layout techniques using the Bootstrap grid system.
Focus on optimizing the website's performance and accessibility.
Learn more about bootstrap's forms.

links used -  https://www.youtube.com/watch?v=Esv4AqWC72E
https://www.youtube.com/watch?v=qNifU_aQRio




<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
