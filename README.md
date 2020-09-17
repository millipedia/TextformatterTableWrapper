# TextformatterTableWrapper

Simple Processwire TextFormatter to wrap a table in a div.  

We use this to stop tables becoming unreadble on small devices by setting a min width and overflow-x: scroll on the wrapper. 

```css

.table-wrapper{  
    max-width: 100%;  
    overflow-x: scroll;
}

.table-wrapper > table{
    min-width: 480px;
}

```

## Installation

[The Processwire way.](https://modules.processwire.com/install-uninstall/)

## How to use

Add this Textformatter in the details tab of the desired Textfield.