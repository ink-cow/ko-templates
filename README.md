# The Koriander templates

Templates for creating comics in Krita.

Different editions incorporate the attributes published by different sources. These attributes differ from publisher to publisher and source to source, but are constructed here in a unique, simple and flexible digital format. Each edition includes a template for a single page, double page spread, and a worksheet.

The files are vector-based, so they are one size fits all. They can be easily resized to match your work requirements following the instructions for resizing below.

They are also configured to use two sets of resolutions: a working resolution and a print resolution, reflecting IRL work with an art board. Without changing the actual pixel dimensions, the alternate working resolution allows you to work with and view the file as if it were a full 11 x 17 inch board, with your target dimension reflecting the ultimate print size.

## How to use

The template has no text labels or borders, just a series of vector shapes to define areas.

![Single page](img/single-page.png)![Double page](img/double-page.png)

The stronger blue outer area is full bleed, while the fainter blue interior defines the extent of the trim area.

The central live area is white, with a series of blue gutters that mark it up into thirds and quarters.

A series of arbitrary blue tabs at the top only remind you to fill in additional information, if needed.

The vector shapes are contained on separate layers so that they can be used to guide other actions. For instance, to quickly trim the page, go to the TRIM layer, then invoke the TRIM TO CURRENT LAYER command. That simple! The LIVE area can be copied or selected to begin building the panel borders.

![Worksheet](img/worksheet.png)

The worksheet is for creating layouts of contiguous pages in whatever manner you see fit, but the idea is to reserve the first column for single pages, and the second two columns for facing pages. That is, your first row may contain pages 1, 2 and 3, with the next row leaving a blank page followed by pages 4 and 5. Such a worksheet an be invaluable for seeing the flow of action in your pages.

![Worksheet usage](img/worksheet-usage.png)

## Editions

* Scratchmore
    
    The Scratchmore edition conform to the attributes of a popular commercial board that you'll find in any art store.

    Keep in mind however that page dimension and ratio vary from publisher to publisher and source to source, so there is no way to create one definitive comic book page template. This template simply reflects the popular commercial board, which you may find is at odds with other recommended formats.
    
    Its live area is 9 x 14 inches.
    
* Damson

    The Damson edition is another commercial board, and the same caution applies to it as its competitor Scratchmore.
    
    Its live area is a bit smaller at 8.75 x 13.75 inches.

## Resizing the board

Resizing the board means changing the actual pixel dimensions for more or less detail.

Determine your preferred target resolution, generally between 300 and 600 dpi, and use the following chart to get your working resolution. The working resolution is always 67% of the target resolution.

Target resolution   | Working resolution
------------------: | ------------------
600                 | 402
550                 | 368.5
500                 | 335
450                 | 301.5
400                 | 268
350                 | 234.5
300                 | 201

Under PRINT SIZE (do nothing in the upper PIXEL section), uncheck ADJUST PRINT SIZE SEPARATELY and enter your working resolution. The pixel width/height above should change, while the print width/height should remain 11 x 17 inches.

![Image resize dialogue](img/image-resize-dialogue.png)

You can use the chart to find your working resolution, or enter the formula as shown above.

## Print resolution

Switching to the print resolution does not resize or alter the art in any way. Check ADJUST PRINT SIZE SEPARATELY and enter your print resolution. Now the pixel dimensions should remain unchanged; this only alters the relative measurements to the set pixel size.



