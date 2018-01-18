---
layout: project
title:  "E-books"
permalink: /projects/e-books
tags: CSS, HTML, Illustrator, Photoshop, RegEx, XML
---

In four years as a full-time e-book developer, my work was all about responsive design and graceful degradation. I developed or rebuilt hundreds of EPUBs, many having content difficult to translate into HTML and CSS, especially given the quirky constraints of e-reading software. 

Such constraints included but most definitely were not limited to the following:

- Many Kindles ignored `margin-top`.
- In paginated reading systems (i.e., most of them), there was no reliable way to keep headings with text they introduced, or images with captions.
- iBooks hid any page it thought was a table of contents.
- Kindles force-justified all paragraph text. If we overrode this, Amazon would flag it as an error.
- Nook Color crashed if the file contained nested `<ol>`s.
- iBooks ignored the `text-align` CSS property on `<p>` unless you wrapped the entire contents of the element in `<span>`.
- Any device or app using Adobe’s Reader Mobile SDK would ignore the `text-transform` CSS property.
- Nooks ignored media queries and crashed if you placed them anywhere except at the bottom of a style sheet.
- Only iBooks reliably rendered fraction glyphs.

In sum: we partied like it was 1999.

For obvious reasons, none of the code for the e-books I made at work is viewable in public GitHub repos. Below, however, are embedded albums of screenshots from a sampling of them.

## Amplify (2014–2015)

Amplify’s middle-school library contains a mix of licensed and public-domain books, documents, and reading packets, some of which are integrated into lessons, some into games, some both. Documents used in lessons typically had definitions attached to specific words, which could work only if the underlying code was clean and semantic. Because it’s an educational product, accessibility was also a primary concern.

Similarly, the automatic line numbering depended on specific markup, especially in plays. Documents used in the game Lexica had quiz questions attached to lines of text, and if a document was incorrectly coded, these would appear at wrong locations.

Poetry is always a challenge in e-reading systems, as are tables. In a nice change from retail e-book production, however, because we controlled the platform, we could be sure that these and typographic niceties such as drop caps and small caps would look consistent on every device and browser we supported.

<a data-flickr-embed="true" data-footer="true"  href="https://www.flickr.com/photos/indiamos/albums/72157692382768055" title="Amplify samples"><img src="https://farm5.staticflickr.com/4606/25894340988_4813407b41_z.jpg" width="640" height="400" alt="Amplify samples"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

## A Book Apart (2013–2015)

*[ABA]: A Book Apart

All ABA titles share a great series design, so although I converted or revised about a dozen e-books for them, I show screenshots from only two below. Most included code samples and lots of figures and captions. They were technically challenging, and it was nerve-racking to know that 99% of the readers would be _developers_. Working with ABA was also my first professional experience using Git and GitHub.

### [_Responsible Responsive Design_](https://abookapart.com/products/responsible-responsive-design) by Scott Jehl (2014)

<a data-flickr-embed="true" data-footer="true"  href="https://www.flickr.com/photos/indiamos/albums/72157692363836625" title="On Web Typography"><img src="https://farm5.staticflickr.com/4715/39723858352_45bc6723e3.jpg" width="403" height="500" alt="On Web Typography"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

### [_On Web Typography_](https://abookapart.com/products/on-web-typography) by Jason Santa Maria (2014)

<a data-flickr-embed="true" data-footer="true"  href="https://www.flickr.com/photos/indiamos/albums/72157664797059008" title="Responsible Responsive Design"><img src="https://farm5.staticflickr.com/4698/27977470539_47b95e69f8.jpg" width="500" height="359" alt="Responsible Responsive Design"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

## NBC Publishing (2012–2014)

The following books are all free, so you can download them and kick the tires yourself. Because they were published by NBC, “enhanced” versions of each, with embedded video files, are also available.

-   _Operation Money: A Financial Guide for Military Service Members and Families_ by Jean Chatzky (2014) – \[[Google Books](https://books.google.com/books?id=HrpPBAAAQBAJ "Operation Money at Google Books"), [iBooks](https://itunes.apple.com/us/book/operation-money/id910815148?mt=11 "Operation Money for iBooks"), [Amazon](https://www.amazon.com/Operation-Money-Financial-Military-Families-ebook/dp/B00MVKUE94 "Operation Money for Kindle"), [Kobo](https://www.kobo.com/us/en/ebook/operation-money "Operation Money at Kobo")\]
-   _His Holiness The Dalai Lama: A Message of Spiritual Wisdom_ (2013) – \[[Google Books](https://books.google.com/books/about/His_Holiness_The_Dalai_Lama.html?id=7Q9OAQAAQBAJ "His Holiness at Google Books"), [iBooks](https://itunes.apple.com/us/book/his-holiness-the-dalai-lama/id725014807?mt=11 "His Holiness for iBooks"), [Amazon](https://www.amazon.com/His-Holiness-Dalai-Lama-Spiritual-ebook/dp/B00FT694AC "His Holiness for Kindle"), [Kobo](https://www.kobo.com/us/en/ebook/his-holiness-the-dalai-lama-1 "His Holiness at Kobo")\]
-   _Election Night: 1960_ by Stephen Battaglio (2013) – \[[Google Books](https://books.google.com/books/about/Election_Night_1960.html?id=ZVS2wu4bNysC "Election Night at Google Books"), [iBooks](https://itunes.apple.com/us/book/election-night-1960/id615631255?mt=11 "Election Night for iBooks"), [Amazon](https://www.amazon.com/Election-Night-1960-Stephen-Battaglio-ebook/dp/B00BNF5BTG "Election Night for Kindle"), [Kobo](https://www.kobo.com/us/en/ebook/election-night-1960 "Election Night at Kobo")\]
-   _Heroes Get Hired: How to Use Your Military Experience to Master the Interview_ by Michelle Tillis Lederman (2013) – \[[Google Books](https://books.google.com/books/about/Heroes_Get_Hired_How_To_Use_Your_Militar.html?id=Kg7HdwKrPIgC "Heroes Get Hired at Google Books"), [iBooks](https://itunes.apple.com/us/book/heroes-get-hired/id593129327?mt=11 "Heroes Get Hired for iBooks"), [Amazon](https://www.amazon.com/Heroes-Get-Hired-Experience-Interview-ebook/dp/B00B02TJEK/ "Heroes Get Hired for Kindle"), [Kobo](https://www.kobo.com/us/en/ebook/heroes-get-hired "Heroes Get Hired at Kobo")\]

## F+W Media (2011–2013)

### _Sew Serendipity: Fresh and Pretty Designs to Make and Wear_ by Kay Whitt (c. 2011–2013)

I’ve enjoyed sewing since I was a child, so converting this book was a labor of love for me. The print edition was colorful and fun, and we wanted the e-book to retain the feel of that but also be _usable_.

<a data-flickr-embed="true" data-footer="true"  href="https://www.flickr.com/photos/indiamos/albums/72157692352075315" title="Sew Serendipity"><img src="https://farm5.staticflickr.com/4623/38851646325_85b99466c0.jpg" width="500" height="360" alt="Sew Serendipity"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

Although I completed the e-book, editorial staff changes orphaned the project, and as far as I know, it was never actually put on sale.

### _Colorwork Mittens and Gloves: From Colorwork Creations by Susan Anderson-Freed_ (c. 2011–2013)

A “CRAFTable,” or project-based sample from a larger book. This was a sort of proof of concept for the product format.

<a data-flickr-embed="true" data-footer="true"  href="https://www.flickr.com/photos/indiamos/albums/72157664796231308" title="Colorwork Mittens and Gloves"><img src="https://farm5.staticflickr.com/4764/25878479858_085c9cd36e.jpg" width="500" height="360" alt="Colorwork Mittens and Gloves"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

\[[Amazon](https://www.amazon.com/Colorwork-Mittens-Gloves-Creations-Anderson-Freed-ebook/dp/B006PHY9LS), [Google Books](https://books.google.com/books?id=eKYjZICUXX4C), [Nook](https://www.barnesandnoble.com/w/colorwork-creations-susan-anderson-freed/1100362038)\]

### _DIY Cocktails: A Simple Guide to Creating Your Own Signature Drinks_ by Marcia Simmons (c. 2011–2012)

This book was poorly converted by an outsourcer and then torn apart and rebuilt by me. You can compare it with the print design using [Amazon’s Look Inside](https://www.amazon.com/dp/1440507503/ref=rdr_ext_tmb "View DIY Cocktails at Amazon.com").

<a data-flickr-embed="true" data-footer="true"  href="https://www.flickr.com/photos/indiamos/albums/72157691567391494" title="DIY Cocktails"><img src="https://farm5.staticflickr.com/4756/39027843184_8141dfc965.jpg" width="375" height="500" alt="DIY Cocktails"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

\[[Amazon](https://www.amazon.com/DIY-Cocktails-simple-creating-signature-ebook/dp/B004MYFL0E/), [Google Books](https://books.google.com/books/about/DIY_Cocktails.html?id=N4Kye2PxpgwC), [Kobo](https://www.kobo.com/us/en/ebook/diy-cocktails-1)\]

## Links

- [99problems](https://github.com/dvschultz/99problems/issues) – Derrick Schultz’s global list of e-reader rendering bugs
