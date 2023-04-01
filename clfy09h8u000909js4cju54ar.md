---
title: "Be selective"
seoTitle: "css selectors"
datePublished: Sat Apr 01 2023 13:24:33 GMT+0000 (Coordinated Universal Time)
cuid: clfy09h8u000909js4cju54ar
slug: selectors
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1680355315151/a58b997b-571a-4b43-8ccd-1229b86f164b.jpeg
tags: javascript, web-development, ineuron, hiteshchoudharylco, anuragtiwarime

---

### CSS is a makeup artist for HTML pages that helps to look beautiful skeletons (HTML). For humans when God creates us at that time we couldn't tell god " please make this part of my Body beautiful or please increase my height this much etc. But as a creator of a website or as developers we have the power to make some websites beautiful by adding some properties to them. For that, we need to be a bit selective. For that, we have to learn about CSS selectors.

* Universal Selectors
    
* Individual Selectors
    
* Class and id Selectors
    
* And Selectors(Chained)
    
* Combined Selectors
    
* Inside an Element selectors
    
* Direct Child Selectors
    
* Sibling selectors
    

**Universal Selectors**: Every browser have some default properties to modify those properties or to use some of the property universally we use this selector. For example, if we consider our html page as a canvas then we can decide that canvas will be red or black or grey or how the whole page's font will look etc.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680200108687/b5db7ad3-e96a-4329-913d-2158936ffb29.png align="center")

**Individual Selectors:** It will select all the sementics tags. For example in your webpage you want that all the paragraphs (p tags) or list items will have **background-color: grey** so if your page contains 100's &lt;p&gt; tags or li tags, they will acquire this grey property.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680200568256/2487a2e5-d15a-4e47-8cc7-488869d826bd.png align="center")

**Class and id Selectors:** Class: It will select everything in the HTML file if a tag uses this class. It starts with a dot <mark>(.)</mark>. In this bellow example if some tags use this warning class they will get a background color and the text color will be white.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680202067056/324b943a-2c6d-4da0-83cc-ac60ffd77f3f.png align="center")

Id: It will select a particular item in the webpage, ideally it should be unique if you don't give it unique it will also work for the forgiving nature of HTML, incase of javascript DOM manipulation it will not work that time it will be a problem. It starts with <mark>(#)</mark>.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680202663014/9edc9573-6997-4829-95f4-5fae1cc1e753.png align="center")

**And Selectors(Chained):** If we go to a shop then often we asked for give me this **and** this same like that we can chain it up with multiple properties. And you may ask why don't we use a name like **bg-blacktext-orange** it will be harder to identify when you write tons of line css I will show you an interesting thing via some snippets

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680328682102/c7afd158-05c1-43e7-a97c-e6c27ff1e78c.png align="center")

this snippet will produce this output

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680328784655/cdc6ac80-d857-4f51-9f37-49664a109fcf.png align="center")

but if we write

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680328937402/d5f8eee5-07d2-4419-9210-cf4e0204e967.png align="center")

It will produce this result

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680329036280/8510ac67-2be0-4d8e-a5f4-46221ea0ec38.png align="center")

so we can see how selective we can be by using this property. You can use this not only with class but also with the IDs for this you need to maintain an order first id then the class name.For that you need do use this snippet

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680329438059/8465d09d-43e9-4685-8566-d9dff3e74f69.png align="center")

**Combined Selectors:** In this case when we want to select more than one property then we use this combined selector to use it you just need to use (,) for multiple selections. For example, if you want to select Span and li in one shot In Javascript then it is very useful.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680330269306/d627b228-f959-450c-8a90-1051bfdcff5b.png align="center")

output

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680330298903/69653a77-46d5-4c7f-bb06-8add6fa2ad32.png align="center")

**Inside an Element selectors:** This selector is for nesting purposes selection. For example, one DIV is there and that div contains two LI and one UL and that UL contains three LI and your job is to select those LI which are under the UL. I know this sounds confusing right?

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680331372893/2edc13da-120f-4f12-abd0-b0e970ec7f19.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680331609627/c13c5585-0275-48ca-a9aa-3e0bad960d85.png align="center")

Here just you need to follow an order. The intuition behind it if there is any UL inside the div it will select that and inside that UL if there is LI it will select that only that it

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680331885126/ea630910-02c8-452a-97e6-7cf581025f44.png align="center")

**Direct Child Selectors:** These we use to select the only direct child. Now what do I mean by a direct child I will show it with a diagram

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680332924626/273139b0-8641-4849-b3fc-02cb51c3e586.png align="center")

to use this we use order by order (&gt;) so if we want to like if I want to select Li under the UL the syntax will be <mark>div&gt;ul&gt;li</mark>

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680340366254/0c9115f5-2bc1-49ab-944e-3c1b994baab7.png align="center")

**output**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680340403921/c5c8f02a-d96f-4cb1-a02a-1cbf9c92cc91.png align="center")

this is another alternative to **Inside an element selector**.

**Sibling selectors:** In this case there are two types

*General Sibling Selector (~)*

*Adjacent Sibling Selector (+)*

**General Sibling Selector:** It uses tlide (~) sign as the separator between the elements. It will affect immedeate siblings mentioned after this (~) sign.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680342889103/60b385ec-9697-4e9e-bf9c-c5f6fa2f50b2.png align="center")

you may ask where it will be use suppose you want that all image after this paragraph will get a border property that time we can use it.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680343066305/169020fe-1b15-4884-a992-730b1e6cc762.png align="center")

output

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680343121068/e65df45a-62a7-4259-982b-29e88c9c8843.png align="center")

**Adjacent Sibling Selector (+):** We use the **plus (+)** sign as the separator between the elements. It will only select the element which is next to the specified tag.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680343451951/a7731379-a441-4259-b906-6d5e5ebecfd7.png align="center")

output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680343544388/91d26dd5-c1c6-41dd-be36-9a5426cb8ecd.png align="center")

### ***Bonus*** :

Do you know why we use # value to give colour to the webpage when it was working fine by giving only the color name? If I write <mark>background-color: Black</mark> and If I write <mark>background-color:#000000</mark> visually both are the same for us but it is different for browsers like chrome, safari, edge they will interpret this may be differently and may not. To set a standard for the color they proposed this and there are 16 million(256\[Red\], 256\[Green\], 256\[Blue\]) colors in this world it not possible to name all 16 million colors for that also this was proposed.