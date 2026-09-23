# CSS Grid Practice — Spanning Rows and Columns

A focused CSS Grid exercise: a 12-box layout with explicit row sizes and items that span several rows or columns.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20site-6B7280?style=for-the-badge&logo=githubpages&logoColor=white)](https://shayan-abrar.github.io/Using-Grid/grid) <!-- live-demo -->

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)

![CSS Grid layout with spanning items](screenshots/preview.png)

## Concepts Practiced

| Property | Usage |
| --- | --- |
| `grid-template-columns: repeat(4, 1fr)` | Four equal-width columns |
| `grid-template-rows: repeat(3, 200px) 50px 50px` | Mixed fixed-height rows |
| `gap: 20px` | Spacing between grid cells |
| `grid-row: span 5` | Box 1 spans all five rows as a tall sidebar |
| `grid-column: span 3` | Boxes 11 and 12 span three columns as full-width strips |

```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(3, 200px) 50px 50px;
  gap: 20px;
}
#box1 { grid-row: span 5; }
#box11, #box12 { grid-column: span 3; }
```

## Run Locally

```bash
git clone https://github.com/SHAYAN-ABRAR/Using-Grid.git
cd Using-Grid
# Open grid.html in a browser
```

## Author

**Shayan Abrar** · [GitHub](https://github.com/SHAYAN-ABRAR) · [LinkedIn](https://www.linkedin.com/in/shayan-abrar/) · [Portfolio](https://shayan-abrar.vercel.app)
