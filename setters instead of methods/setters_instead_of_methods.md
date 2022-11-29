## Problem description

Why setters instead of methods? After all, I am constantly mistaken, for example, writing

`runtime.layout.scrolX = 13;`

instead of

`runtime.layout.scrollX = 13;`

If there was a method instead of a setter, I would see an error in the console:

`runtime.layout.setScrolX(13);` - there is no such method, great! I don't spend a lot of time looking for a bug.

You've already done well by adding the `scrollTo(x, y)` method, but what about the rest? `instance.width` instead of `instance.setWidth()`, `text.fontFace` instead of `text.setFontFace()`. Please tell me how can I get rid of the waste of time when on writing the wrong setter name I'm just looking for where I went wrong?

## Attach a .c3p

There is not.

## Steps to reproduce



## Observed result

`runtime.layout.scrolX = 13;`

![observed](https://user-images.githubusercontent.com/91274932/204441366-49079540-8109-4b9f-8c32-524eb4ea6c6a.png)

I don't get any error or working code.

## Expected result

`runtime.layout.setScrolX(13);`

![expected](https://user-images.githubusercontent.com/91274932/204441503-3c2847f3-8486-4990-843d-7b1f4973bef9.png)

I see the mistake right away and understand where I made it and go to fix it right away, without spending a lot of time figuring out the reasons.

## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r319-2b

## System details

<details><summary>View details</summary>



</details>
