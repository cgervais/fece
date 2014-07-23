Front-end coding exercise
=========================

### Instructions

* Use the following data to populate a grid/table:

```
var people = [
	{
		id: 0,
		active: true,
		name: 'John Smith',
		age: 35,
		email: 'john.smith@gmail.com'
	},
	{
		id: 1,
		active: true,
		name: 'John Smith',
		age: 35,
		email: 'john.smith@gmail.com'
	},
	{
		id: 2,
		active: true,
		name: 'John Smith',
		age: 35,
		email: 'john.smith@gmail.com'
	},
	{
		id: 3,
		active: false,
		name: 'John Smith',
		age: 35,
		email: 'john.smith@gmail.com'
	},
]
```

* The display should look like:

                                                               [New person]

Active | Name               | Age | Email                        | (controls)
------ | ------------------ | --- | ---------------------------- | --------
[*]    | John Smith         | 35  | john.smith@gmail.com         | [E] [D]
[*]    | Mary Jones         | 28  | mary.jones@gmail.com         | [E] [D]
[*]    | Michael Miller     | 40  | michael.miller@gmail.com     | [E] [D]
[ ]    | Elizabeth Johnson  | 32  | elizabeth.johnson@gmail.com  | [E] [D]

[E] can be an icon that represents editing, and [D] can be an icon that represents deleting

* The functionality should be as follows:
The data in the grid should always reflect the data that is in the people array.  It should never be out of sync.
When you click the [New person] button a blank row will appear as the first item in the table/grid.  Instead of an [E] button it will be a [S] save button (find an icon).
When you edit a row, the [E] icon will be replaced with an [S] icon to allow you to save/sublit the new person.
If you click the [D] button on any row, it will be removed from both the display and the people array.

* Use Bootstrap, and any JavaScript libraries you feel comfortable with (bonus for using AngularJS).  We are looking for ease of maintenance, clean code, and a preference in using the right libraries for the right task.