#Book-Catalog-ITC-Project
### Semester 1 B.Tech Computer Science & Engineering
**Course:** Introduction to Tech Computing (ITC)  
**Group:** Group 4  
**Project:** Project #9  

---

## Project Description
A responsive personal catalog webpage that lists books a student owns or has read, showcasing details such as cover images, authors, genres, ratings, and full book summaries. The project is designed with a modern dark theme inspired by professional developer portfolio websites, built strictly using beginner-friendly semantic HTML5 and CSS3 (zero JavaScript).

---

## Equal Work Division (3 Team Members)

The project codebase is divided equally (~33% per member) across distinct UI modules:

| Member Name | Student ID | Assigned Modules & Sections | Code Portions & Files | Approx. Lines |
| :--- | :--- | :--- | :--- | :--- |
| **Avanish Kumar** | `202610101200012` | **Header, Navbar & Overview/Search**<br>• Webpage Header with title & tagline<br>• Navigation Bar with internal jump links<br>• Library Overview Banner & Statistics Chips<br>• Quick Search input box & focus state | `team-split/avanish/`<br>• `avanish-part.html`<br>• `avanish-part.css`<br>*(also in main index.html & style.css)* | **~172 lines**<br>(31%) |
| **Nitin Bhargav** | `202610101200010` | **Book Catalog & 6 Card Grid**<br>• Catalog Section Header & Subtitle<br>• Flexbox Book Grid container<br>• 6 Book Cards (Covers, Titles, Authors)<br>• Genre Tags & Star Ratings (★/☆)<br>• Hover Lift & Description reveal | `team-split/nitin/`<br>• `nitin-part.html`<br>• `nitin-part.css`<br>*(also in main index.html & style.css)* | **~202 lines**<br>(35%) |
| **Shubham Kumar** | `202610101200011` | **Add-Book Form, Design System & Footer**<br>• CSS Variables (:root), Reset & Body<br>• Add-Book Form Section & 6 Input Fields<br>• Textarea & Accessible Label bindings<br>• Neon Focus Glow & Action Buttons<br>• Footer with copyright & team credits | `team-split/shubham/`<br>• `shubham-part.html`<br>• `shubham-part.css`<br>*(also in main index.html & style.css)* | **~213 lines**<br>(34%) |

---

## Key Features Implemented

1. **Clean Card-Based Grid:** 6 books displayed with cover images, genre badges, titles, authors, and golden star ratings using HTML entities (`&#9733;` and `&#9734;`).
2. **Interactive Hover Effects (No JavaScript):** Smooth card elevation (`transform: translateY(-6px)`) and hidden book summary expansion (`display: block` on hover).
3. **Overview & Library Stats:** Quick summary chips showing total books, unique genres, and average rating.
4. **Accessible "Add Book" Form:** Clean form structure (`action="#" method="get"`) with 6 inputs, focus glow, and styled submit/reset buttons.
5. **Dark Mode UI:** Modern slate palette defined with CSS custom properties (`:root`).

---

## Project File Structure

```text
Book-Catalog-ITC-Project/
├── index.html        # Complete merged webpage (open in any browser)
├── style.css         # Complete merged stylesheet
├── README.md         # Project documentation & team split
├── images/           # Book cover images (book1.jpg to book6.jpg)
└── team-split/       # Individual member modules
    ├── avanish/      # Avanish's HTML & CSS (Header, Navbar, Overview, Search)
    ├── nitin/        # Nitin's HTML & CSS (Book Catalog, 6 Cards, Stars)
    └── shubham/      # Shubham's HTML & CSS (Design System, Form, Footer)
```

---

## How to Run
1. Open the project folder in VS Code or Windows Explorer.
2. Double-click **`index.html`** or right-click &rarr; **Open with** &rarr; your favorite browser (Chrome, Edge, Firefox).
3. No server or installations required!
