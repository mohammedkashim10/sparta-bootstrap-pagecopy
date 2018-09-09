# Volume Network Copy

#### By Mohammed Kashim

## Task:

Creating and styling a webpage to make it look identical in appearance to the Volume Network homepage (aside from the colour scheme).

## Tech Used

HTML, CSS, with Bootstrap framework, using the program Atom.

## Challenges

I had some issues with the navbar in that the right-most side went beyond the edge of the webpage. This may have been caused by the button on the end. I added a margin-right to move the elements of the navbar to the left and also tried to set the width of the navbar to a fixed value, while subsequently setting the width of following containers to 100% but this seemed to have no effect. Here you can see the protruding element. The white space is the section beyond the edge of the webpage.

![MacDown Screenshot](/Users/tech-a36/Desktop/navbar-beyond.png)

I also initially had trouble with the logo in the navbar; when it was input, its position was off. I therefore used the following code to overcome this issue.

```css
.navbar-brand img {
  width: 95px;
  height: 95px;
  transform: translate(-14px,-36px);
}
```
## Takeaways

During this project I improved my understanding of targeting specific elements in css. For example, in the codeblock above I had to specifically target the image in the navbar-brand class as opposed to the entire class itself.

## Link to GitHub

Live page: https://mohammedkashim10.github.io/sparta-bootstrap-pagecopy/

## How to Download

Clone the repository: copy the link of the repository from GitHub (user: mohammedkashim10) and carry out the command 'git clone **link**' in your terminal in your desired location.