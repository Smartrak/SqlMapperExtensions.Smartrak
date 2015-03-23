# SqlMapperExtensions.Smartrak
SqlMapperExtensions with Smartrak enhancements


[ManualKey]

Used the same as [Key], but the initial value (for Insert) must be set in your code.


[TablePerType]
Set on the base (abstract) class in an inheritence tree to use table per type style storage.
You'll need to have a type field on the base class which you'll need to use yourself to decide what type each row is.
Each type needs a [Table] attribute