# xml-to-csv-converter
A single-file utility to convert XML sitemaps to CSV and clean up wrapped URLs.
The Sitemap Scrubber: XML to CSV Made Easy

Tired of messy XML sitemaps? This is your quick fix! It's a tiny, powerful utility built into a single HTML file that cleans up your sitemap data and turns it into a perfect spreadsheet-ready CSV.

Best part? It runs entirely in your web browser. No installs, no command line—just open the file and start converting.

What It Can Do For You

**This little tool is all about saving you time and headaches with data cleanup:**

1. Smart Sitemap Handling

It figures out the XML: Whether you give it a standard URL Sitemap (<url>) or a large Sitemap Index File (<sitemap>), it knows exactly what to do.

Time Saver: It takes that technical <lastmod> timestamp and automatically splits it into two useful columns: Date Modified and Time Modified. This makes sorting and filtering in Excel or Google Sheets way simpler.

2. Perfect CSV Exports

You choose the format: Easily convert the parsed data into a CSV using the delimiter you need (Comma, Semicolon, Tab, or Pipe). Great for working with different spreadsheet programs (hello, European Excel users!).

Bonus Cleanup: Got URLs wrapped in Google search parameters (like https://www.google.com/search?q=your-real-url)? Just check the "Clean URLs" option to instantly strip off the wrapper and get the clean destination URL.

Get Started in Seconds

**It's genuinely just two steps:**

Grab the file: Download or clone the xml_to_csv_converter.html file to your computer.

Run: Open xml_to_csv_converter.html in Chrome, Firefox, Safari, or any modern browser.

Then, paste your XML, pick your delimiter, and hit Convert XML & Download File. Done!

Under the Hood

**We kept it simple for maximum speed and zero dependencies:**

HTML5

Vanilla JavaScript: All the heavy lifting (parsing and conversion) is done right here.

Tailwind CSS (via CDN): For a clean, modern look that works well on mobile and desktop.

Zero dependencies, zero hassle.
