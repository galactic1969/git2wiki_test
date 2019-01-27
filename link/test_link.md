# image syntax
## some image syntax in a line

![image1](../images/logo01.png) ![image2](../images/logo02.png) ![image2](../images/logo01.png) test

## an image syntax in a line

![image1](../images/logo02.png) test

## invalid image link

test ![image1](../images/invalid.png)
test ![image1](../images/logo01.png) ![image2](../images/invalid.png) ![image2](../images/logo01.png)

# link syntax

## a link syntax in a line

[link1](./inbound_link_depth/test_inbound_link.md) test

## some link syntax in a line

test [link1](./test_inbound_link.md) と  [link2](./inbound_link_depth/test_inbound_link.md)

## invalid link

test [link1](./invalid.md)
[link1](./test_inbound_link.md) と  [link2](./inbound_link_depth/invalid.md) test

## other link

[google](https://google.co.jp)
[google](https://google.co.jp) と [yahoo](https://yahoo.co.jp)

# file syntax

## a file syntax in a line

[file](../files/samplefile2.txt) test

## some file syntax in a line

test [file](../files/samplefile.txt) と [file](../files/samplefile2.txt)

## invalid file link

test [file](../files/invalid.txt)
[file](../files/samplefile.txt) と [file](../files/invalid.txt) test
