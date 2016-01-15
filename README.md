# Form Builder Field Cloner
Allows for fast and easy replication of Form Builder fields and fieldsets in bulk. The most common use case is creating repeater-like sets of fields. You can create a single fieldset with a group of fields under it and then enter the number of clones you would like. The clones will be conveniently numbered for you. Using collapsed fields or some combination of collapsed fields and showIfs, this can give you something approximating repeating fields.
 
## Instructions
Install the module. Create the field or set of fields that you wish to clone. If cloning a set of fields, you must create a fieldset to enclose them. Edit the fieldset (if cloning a set) or the individual field (if cloning just one field) and scroll to the bottom of the page where you will see a new "Clone" input field. Enter an integer value for the number of clones you would like to create, and then save the field. That's it!

If you need to change something in one of the fields' settings, you can blow away all of the copies in the form editor, edit the original, and re-clone (FormBuilder will retain any saved entries for those fields as long as the new fields have the same names as the old).

### Limitations
Fields are always added to the bottom of the form, which can be a source of frustration if you have a lot of fields and need to manually reorder them. It's best to clone the field(s) before you've added fields below it. I'm looking into a solution for this.