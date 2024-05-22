# Sizing Elements and Handling Overflow 
 ### Intrinsic Size
- Some elements have a natural size set by default, we call it Intrinsic Size.

### Extrinsic Size
- If we set a Specific Size to an element, we call an Extrinsic Size.

## Handling Overflow
#### **CSS Overflow Property**
- Content overflow can be handled using the CSS overflow property.

- The overflow property has the following values:

### ***visible(default)*** - CSS tries to avoid data loss. Hence, the overflow: visible; is the default value for it.
### ***hidden*** - The overflow is clipped, and the rest of the content will be invisible.
### ***scroll*** - The overflow is clipped, and a scrollbar is added to see the rest of the content.
### ***auto***- It is similar to scroll, but it adds scrollbars only when necessary.
---
## **overflow-x & overflow-y**
There are two other CSS properties similar to overflow, which is used for handling in any one particular direction.

#### ***overflow-x*** - To handle overflow in the horizontal direction.
#### ***overflow-y*** - To handle overflow in the vertical direction.
---
## Min & Max Sizes
### _Min size_
- The min-height & min-width CSS properties can be used to define the minimum sizes of an element.

```
.paragraph {
  min-height: 150px;
}
```

### _Max size_
- The max-height & max-width CSS properties can be used to restrict the sizes of an element.

```
.paragraph {
  max-height: 150px;
  max-height: 180px;
}
```

### Min & Max Sizes with Overflow
If the content needs a larger than maximum height, the overflowing of content can be observed

## _A Note on Meta Element_

```

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
  </head>
</html>
```

The meta element is used to provide additional important information about HTML document.

#### **Name** - specifies the type of meta element it is, what type of information it contains. viewport gives instructions to browsers on how to control the page's dimensions and scaling.
#### **Content** - specifies the actual meta content.
---
#### _In mobile devices, you may experience this issue, so it is a good practice to include viewport meta element in the HTML._
