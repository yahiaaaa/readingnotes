# Tables in HTML

![alt text](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/Html-Tables.jpg  "title")


The <table> HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

<table>

    <thead>

        <tr>

            <th colspan="2">The table header</th>

        </tr>

    </thead>

    <tbody>

        <tr>

            <td>The table body</td>

            <td>with two columns</td>

        </tr>

    </tbody>

</table>

# JS Constructor Functions
A constructor is a function that creates an instance of a class which is typically called an “object”. In JavaScript, a constructor gets called when you declare an object using the new keyword.

The purpose of a constructor is to create an object and set values if there are any object properties present. It’s a neat way to create an object because you do not need to explicitly state what to return as the constructor function, by default, returns the object that gets created within it.

What happens when a constructor gets called? In JavaScript, here’s what happens when a constructor is invoked:

A new empty object is created

this keyword starts referring to that newly created object and hence it becomes the current instance object

The newly created object is then returned as the constructor’s returned value 

var objectName = { 

    propertyKey1: value1,

    propertyKey2: value2,

    functionKey: function () { 

        return this.propertyKey1 + ' ' + this.propertyKey2;

        } 
        
};
