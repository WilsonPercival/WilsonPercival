## Problem description

I can't export project with simple minification.

Here is an excerpt from the documentation:

https://www.construct.net/en/make-games/manuals/construct-3/scripting/guides/advanced-minification

`Simple mode eliminates whitespace and does simple adjustments like renaming local variables to shorter names. This does not affect how any of the code is run so is always safe to use.`

## Attach a .c3p

[private_field_simple_minification_bug_r319_2b.zip](https://github.com/WilsonPercival/WilsonPercival/files/10044467/private_field_simple_minification_bug_r319_2b.zip)

## Steps to reproduce

1. Open a project.
2. Export it to Web (HTML5) with simple minification.

## Observed result

![observed](https://user-images.githubusercontent.com/91274932/202791764-77cfdb83-0e56-42c9-9c2c-cee0002b4146.png)

/str/scripts/project/main.js:3:1: ERROR - [JSC_PARSE_ERROR] Parse error. '}' expected
  3| 	#runtime;
     	^

1 error(s), 0 warning(s)

## Expected result



## More details



**Affected browsers/platforms:** Chrome

**First affected release:** broke in r319-2b

## System details

<details><summary>View details</summary>



</details>
