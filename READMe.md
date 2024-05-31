# Bootstrap
**Definition:** Bootstrap is a free and open-source front-end framework for developing websites and web applications. It includes **HTML, CSS, and JavaScript** components for creating responsive and mobile-first web designs.


**Components:** Provides pre-built HTML, CSS, and JavaScript components for common UI elements like buttons, forms, navigation, and many more.

**Responsiveness:** Designed with mobile-first principles, ensuring websites adapt to different screen sizes.

**Popularity:** The most popular front-end framework for web development.

**Ease of Use:** Speeds up development by providing pre-built components and reducing the need to write code from scratch.

**Grid System:** Uses a 12-column grid layout to structure web content efficiently.

**Note:**
 - Bootstrap 5 is latest stable version and latest version is 5.3
 - Bootstrap 5 supports all major browsers except Internet Explorer 11 and down.

**Bootstrap Breakpoint**
|Breakpoint | Class infix | Dimensions |
|---|---|---|
|X-Small | - | <576px|
|Small | sm | >=576px|
|Medium | md | >=768px | 
|Large | lg | >=992px | 
|Extra Large | xl | >=1200px | 
|Extra Extra Large | xxl | >=1400px|

# Bootstrap Environment Setup:

 - Create an HTML File
 - open bootstrap official website [Open Official Website](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
 - Link Bootstrap CSS file
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" >
```
 - Link Bootstrap JavaScript files
```
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js"></script>
```

# container class
The .container class creates a fixed-width container that is responsive. The width of the container adjusts according to the viewport size, maintaining a margin to the sides to center the content. This type of container is commonly used for fixed-width layouts.
 - **Content Containment:** They establish a designated area to hold your website's content, providing a clear visual distinction between the content and the outer edges of the viewport (the visible portion of the browser window).
 - **Padding:** Containers automatically add padding to the content they enclose, creating a visually pleasing separation between the content and the container's edges. This padding helps enhance readability and user experience.
 - **Alignment (Optional):** In Bootstrap versions 3 and earlier, containers offered optional horizontal centering of content within the viewport. However, this behavior was removed in Bootstrap 4 and later to provide more control over layout using the grid system.

# container-fluid class
The .container-fluid class creates a full-width container that spans the entire width of the viewport. This is useful for layouts that need to utilize the full width of the screen.

**Container class Breakpoint**
|Class | Extra Small (<576px) | Small (>=576px) | Medium (>=768px) | Large (>=992px) | X-Large (>=1200px) | XX-Large (>=1400px) |
|---|---|---|---|---|---|---|
|.container|100% | 540px | 720px | 960px | 1140px | 1320px | 
|.container-sm | 100% | 540px | 720px | 960px | 1140px | 1320px |
|.container-md | 100% | 100% | 720px | 960px | 1140px | 1320px |  
|.container-lg | 100% | 100% | 100% | 960px | 1140px | 1320px |
|.container-xl | 100% | 100% | 100%| 100% | 1140px | 1320px |
|.container-xxl | 100% | 100% | 100%| 100% | 100% | 1320px |
|.container-fluid |  100% | 100% | 100%| 100% | 100% | 100% |

# Bootstrap Layout (Grid - row & col)
 - The Bootstrap grid system is a powerful and flexible layout system that allows developers to create responsive and mobile-first layouts using a series of containers, rows, and columns. The system is based on a 12-column layout and provides various classes to control the size and alignment of elements across different screen sizes.

**Basics of Bootstrap Grid System**
1. **Containers:** Containers are the fundamental building blocks of the Bootstrap grid system. They house the rows and columns and are required to ensure proper alignment and padding. There are two types of containers.
 - .container: A fixed-width container with responsive breakpoints.
 - .container-fluid: A full-width container that spans the entire width of the viewport.
2. **Rows:** Rows are used to create horizontal groups of columns. They must be placed within a container and use the .row class.
3. **Columns:** Columns are the building blocks of the grid system. They are used within rows and can be sized using classes like .col-md-6. Columns span a certain number of the 12 available grid columns.