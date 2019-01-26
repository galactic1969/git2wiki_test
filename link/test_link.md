# image syntax
## some image syntax in a line

test ![image1](../images/folder.png) ![image2](../images/rocket.png) ![image2](../images/folder.png)
![image1](../images/folder.png) ![image2](../images/rocket.png) ![image2](../images/folder.png) test

## an image syntax in a line

test ![image1](../images/folder.png)
![image1](../images/folder.png) test

# link syntax

## a link syntax in a line

test [link1](./test_inbound_link.md)
[link1](./inbound_link_depth/test_inbound_link.md) test

## some link syntax in a line

test [link1](./test_inbound_link.md) と  [link2](./inbound_link_depth/test_inbound_link.md)
[link1](./test_inbound_link.md) と  [link2](./inbound_link_depth/test_inbound_link.md) test

## other link

[google](https://google.co.jp)
[google](https://google.co.jp) と [yahoo](https://yahoo.co.jp)

# file syntax

## a file syntax in a line

test [file](../files/samplefile.txt)
[file](../files/samplefile2.txt) test

## some file syntax in a line

test [file](./files/samplefile.txt) と [file](./files/samplefile2.txt)
[file](../files/samplefile.txt) と [file](../files/samplefile2.txt) test
