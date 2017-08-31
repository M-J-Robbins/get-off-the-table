# get-off-the-table
Building HTML emails without &lt;tables&gt;

I'm trying to create an email template using a number of common style components, but without the use of any layout tables.

* 600px centered container
* Heading tags
* Paragraph tags
* Images
* Nested section with different width and background
* Multi column layout
* Ordered and Unordered lists
* Divider line
* CTA button
* Additional container outside of the main container

The main issue here is that Outlook doesn't render HTML or CSS correctly as they user Microsoft Word as a rendering engine.  However I believe we can manipulate Outlook into working with a `<div>` based layout using `mos-` code.
