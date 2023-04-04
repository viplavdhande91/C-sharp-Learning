
# Sealed Methods In C#



1. When the derived class overrides a base class method/variable/property/event, then the new method/variable/property/event can be declared as sealed.


2. Sealing the new method prevents the method from further overriding.


3. An overridden method can be sealed by preceding the override keyword with the sealed keyword.



# Why use Sealed Methods?



1. Sealed method is always an override method of child class.


2. We cannot again override the sealed method.


3. Sealed method is only available with Method Overriding.

4. Sealed keyword is not available with the method hiding.


5. Sealed is used together with override keyword.
6. We cannot make normal methods as sealed.

