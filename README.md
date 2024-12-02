# Time Table and Grid Layout Example

This repository demonstrates the implementation of a time table, a grid-based image gallery, and a checkerboard layout using HTML and CSS.

## Features

### Time Table
- Displays a structured table representing a sample timetable.
- Includes lunch breaks and subject allocations for different days.
- **Responsive Layout**: Table rows and columns adjust for clear visualization.

### Image Gallery
- Displays a grid-based gallery of images.
- Uses CSS Grid for consistent spacing and alignment.
- **Dynamic Styling**: Easy to customize image size and gap.

### Checkerboard Layout
- A checkerboard pattern created using a grid of black and gray tiles.
- **Reusable Design**: Customizable tile size and color scheme.

## How It Works

### Time Table
1. **HTML Table**:
   - `table` element structures rows and columns.
   - `th` and `td` elements define headers and data cells.
   - Merged cells (`colspan` and `rowspan`) create a visually appealing layout.
2. **CSS Styling**:
   - Borders and padding enhance table readability.
   - Centralized alignment using Flexbox.

### Image Gallery
1. **HTML Grid**:
   - `div` elements represent individual images in the gallery.
   - Images sourced from the `Images` directory.
2. **CSS Grid**:
   - A `grid-template-columns` property defines a 3-column layout.
   - Gaps between images provide clear separation.

### Checkerboard Layout
1. **HTML Divs**:
   - Alternating `div` elements styled as black (`b`) and gray (`w`) tiles.
2. **CSS Grid**:
   - `grid-template-columns` creates an 8x8 grid.
   - Tile dimensions and colors are adjustable.

## Technologies Used

- **HTML**: Structure for tables, grids, and layouts.
- **CSS**: Styling for table borders, grid spacing, and color patterns.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Navigate to the project directory:
   ```bash
   cd <repository-folder>
3. Ensure the styles.css file is in the correct location: Update the <link> tag in the HTML file if needed.
4. Open the index.html file in a web browser.

## Usage

- **Time Table:** View a pre-designed timetable layout with hours and subjects.
- **Image Gallery:** Display and customize images in the gallery grid.
- **Checkerboard:** View an 8x8 checkerboard pattern for design or visual testing.

## Screenshot

**Timetable**    
  ![image](https://github.com/user-attachments/assets/354ea343-09f6-42a8-ad44-c7537f1fdc4f)

**Image Gallery**  
  ![image](https://github.com/user-attachments/assets/4f6d51c1-fddd-4ca0-95b5-7e57ffd963f5)

**Checkerboard Layout**  
  ![image](https://github.com/user-attachments/assets/24699d3b-10e8-450b-99bd-1622c8165d47)

## Limitatons

- **Dynamic Data:** Table content is static and needs manual updates for real-world applications.
- **Image Paths:** Ensure correct paths for the image files `(Images/E1.jpg)`.
- **Checkerboard Size:** Grid size is fixed to 8x8 but can be adjusted in CSS.
