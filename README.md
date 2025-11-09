# Frontend Mentor - Single price grid component

This is a solution to the [Single price grid component on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📸 Screenshot

![Screenshot of my solution](./preview.png)

---

## 🔗 Links

- **Solution URL:** [](#)
- **Live Site URL:** [](#)

---

## 💻 My process

### Built with
- Semantic **HTML5** markup  
- **CSS3** (Grid layout, custom fonts)  
- Responsive design principles  

---

## 🧠 What I learned

While working on this project, I reinforced my understanding of:
- Using **semantic HTML** (`<main>`, `<section>`)
- Creating **centered layouts** with Flexbox  
- Designing **consistent color palettes**

Here’s a little code snippet I’m proud of:

I'm very proud of being able to use grid layout for the first time, even if it's something so simple

main{
    display: grid;
    grid-template-columns: 350px 350px;
    grid-template-rows: 240px 280px;
    margin: auto;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.192);
    border-radius: 10px;
}

.introSection{
    background-color: rgb(255, 255, 255);
    grid-column-start: 1;
    grid-column-end: 3;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}