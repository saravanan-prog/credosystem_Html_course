### HTML List
 A Html list is an arranged elements ordered or unordered.

##  TYPES:
  - undorder list 
  - order list
  - description list 

####  1.  UNORDER LIST
    
-  👉 Used to create a `bulleted list` first then change the type later.

#### Attributes:
```
      <ul type="disc">  <!-- Default -->
      <ul type="circle">
      <ul type="square">
```
####    Example:
```
      <ul>
          <li>Apple </li>
          <li>Orange </li>
          <li>Grapes </li>
      </ul>
```
####  2.  ORDER LIST
    
  -  👉 Used to create a `numbered list` first then change the type later.
  #### 👉 Attributes
    
          <ol type="1">   <!-- Numbers (default) -->
          <ol type="A">   <!-- Capital Letters -->
          <ol type="a">   <!-- Small Letters -->
          <ol type="I">   <!-- Roman Capitals -->
          <ol type="i">   <!-- Roman Small -->
          <ol start="5">  <!-- Used to start numbering from a different number. -->


    ✅ Example:
        <ol>
              <li>Apple </li>
              <li>Orange </li>
              <li>Grapes </li>
        </ol>


####  3.  DESCRIPTION LIST
    

      <dl>          --> description list
        <dt> </dt>  --> descript title
        <dd> </dd>  --> description data
      </dl>