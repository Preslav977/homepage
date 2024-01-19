# homepage

1. This is the final result of the project Homepage

![Screenshot_2024-01-19_10-19-01](https://github.com/Preslav977/readme-repository/assets/119291608/40f4bb05-ed89-4e41-bc61-7b07a6317d71)

In this project the covered concepts where Transorm, Transition some Accessibility concepts like Semantic HTML, Accessible colors, Meaningful text, Responsive concepts like Nature Responsiveness (mostly flexbox and grid), Responsive Images, Media Queries.

1.1. The first section of the project, contains a container that is slanted, this was done with using a skewY and transform-origin, this allowed the container to "stay" in the left top, and had a effect of being slanted with certain degrees.

1.2. The most trouble here was on how to make the image and the container with personal information to shrink and expand, i could done better here, the shrinking of the personal information container wasn't done soomthly and when it reaches certain pixels it just goes below the image, because of using the flex-wrap.

One thing forgot to mention was the paragraph for the name, it made sense to be on top of the image, what i should have done is, maybe to use flex to stay in place, so it can actually shrink and expand and not move.

And it caused an isssue later, because i had to use a lot of media queries to make the image and personal information container to had some space between the projects and that.

1.3. The middle section contains the project, this was done with using grid-template-cows, auto-fill, minmax, this maked the project take 300px when they are not shrunk and take 1 fraction unit, whe they are shrunk this allowed the projects to be in one column when certain pixes are reached and it could look better on a mobile.

One problem i had is i tried to used one container to wrap the projects using flex to make the container stay centered, if this result was achieved i could not used margin around the projects, definitely this could be done differently.

1.4. The last section was a footer, this could also be done differently, since it doesn't have a smooth transition to shrink the text and when it reaches certain pixels to go below the image.

1.5. For accesability the first thing i did is, used semantic html and i tried to use the header from 1 do 5, for different sections, for meaningful text i haven't putted any descriptions since it wouldn't make any sense to name them after what they are called.

Explaning, if i have a project with name Battleship, i think it's descriptive enough and it doesn't need to be called the same thing in the alt tag of the image.

For accessiability color, i used simple colors so the text can be read without much trouble and i confirmed this by using dev tools Accessiability tab in the Firefox, same thing could be said for different accesiability rules.

I haven't tested the tab-index, which was my bad but if i did i could know if my DOM tree structure is good or not.

1.6. I used briefly transofm and transition to make the social media icons to make 360 degrees.

1.7. Responsive, probably i shouldn't have abused a lot of Media Queries, to fix my problem with what i had in the header section of the project, i think there was also a problem that parapgrah with text My Work got hidden, because of that, i see a ton of improvmenent could have been made.

What i also learned, that using min or max for height and width, it's definitely better with flex, so i can actually shrnk and expand natuarally, instead of getting squished.