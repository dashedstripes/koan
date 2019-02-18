# Grid

```css

/* Container */

.container === 
  max-width: $grid-max-width;
  margin: 0 auto;
  padding: 0rem $grid-gutter;

/* Row (place inside container) */
.row ===
  display: flex;
  flex-wrap: wrap;
  margin-left: -$grid-gutter / 2;
  margin-right: -$grid-gutter / 2;

/* Columns (place inside row) */

.col-{breakpoint}-{value}
.col-{sm (small) | md (medium) | lg (large) | blank)-{1-12}

.col-6 === 
    width: 50%;
    padding: 0rem $grid-gutter / 2;

```