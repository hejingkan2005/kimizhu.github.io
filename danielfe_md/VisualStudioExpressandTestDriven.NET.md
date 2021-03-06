<div id="page">

# Visual Studio Express and TestDriven.NET

[Dan Fernandez -
MSFT](https://social.msdn.microsoft.com/profile/Dan%20Fernandez%20-%20MSFT)
6/1/2007 1:39:00 AM

-----

<div id="content">

\* Updated with follow up post on [technical
information](http://blogs.msdn.com/danielfe/archive/2007/06/01/testdriven-net-and-express-technical-information.aspx) in
response to the comments.

While I’m not a lawyer, my team owns Visual Studio Express and I wanted
to respond to the concerns expressed by some over our recent
communications with Jamie Cansdale of TestDriven.NET. TestDriven.NET is
a 3rd party add-in to Visual Studio that provides testing functionality
in Visual Studio. To be clear, we have no issue with the product (or
Jamie for that matter), or its sale for use in
<span class="underline">professional</span> versions of Visual Studio.
However, Jamie has also made available a version of his product that
extends the Visual Studio Express Editions which is a direct violation
of both the EULA and “ethos” of the Express product line.

As you may remember from my previous posts, Visual Studio Express was a
labor of love. It was a [small miracle getting Express to be available
both for free and for commercial
use](http://blogs.msdn.com/danielfe/archive/2004/04/14/113582.aspx) for
customers let alone the [engineering work to get it up and
running](http://blogs.msdn.com/danielfe/archive/2006/08/10/the-hobbyist-renaissance-at-microsoft.aspx), We
made a business decision to not allow 3rd party extensibility in
Express. The reason we’re able to offer Express for free and even let
developers build commercial applications with Express is because we
limit 3rd party extensibility of Express, specifically by removing
support macros, add-ins, and VSIP packages. Unfortunately, in this one
instance, we have one company that chose to exceed the license grant and
develop additional features into the Express products that are not
allowed. Additionally we have over 300 VSIP partners with over 1,000
<span class="underline">legal</span> Visual Studio extensions that
cannot extend Express. It doesn’t make business sense when our biggest
and best partners are legally unable to extend Express, yet Jamie’s
company can.

As for Jamie, we’ve been asking him in multiple emails and conference
calls to stop extending (just Express) since before Visual Studio 2005
even shipped. We even got the General Manager of Visual Studio to
personally talk to him on the phone to plead with him to remove Express
extensibility. Closely following that, Jamie took the violations to
heart and removed Visual Studio Express extensibility for several
months. Only recently did he decide to add Express support back to
TestDriven.NET and only after another round of conversations and close
to two years of trying to avoid escalating this situation, we felt
compelled to deliver our message in a different form.

**The Express Customer  
**The vast majority of our customer base, now with 14 million
downloads, isn’t even professional developers, its non-professionals.
In fact over 80% of Express registrants don’t describe themselves as a
“developer”. From a total number perspective, beginners are the
largest segment of Express customers and they still find Express too
complex, it has too many features, and they see development as a means
to an end (I just want to create my kids soccer league Web site). Our
Express customers haven't been asked for unit testing or extensiblity in
much the same way as I didn't ask or even know to ask when I grew up
programming BASIC on an Apple IIe. Heck even professional developers
with years of programming experience can't program
[FizzBuzz](http://www.codinghorror.com/blog/archives/000804.html). 

It’s unfortunate that this happened, but as you can see, we have been
very patient with Jamie and it’s our hope he will remain in compliance
of the Visual Studio Express Editions license agreement.

If the choice was between not ever having released Visual Studio Express
(or not releasing it in the future) or having Visual Studio Express with
an explicit limitation to block extensibility, which would you chose? As
an advocate for the (wholly neglected) beginner customer and as an
employee that understands Microsoft is a business at the end of the day,
it seems like a perfectly reasonable tradeoff to make that, in the end,
provides the best tools possible to an entire class of customer that may
never have picked up programming without it.

</div>

</div>
