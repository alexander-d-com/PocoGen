# PocoGen

This T4 template is intended to be used with Oracle.ManagedDataAccess, the full path to the dll is needed in the assembly declaration, otherwise the compiler will search it in the .NET Framework 4 folder. 

The extended connection string is needed for the Oracle.ManagedDataAccess driver to work from a class library. 

The ToTitleCase method is also removing  the undescores to match naming conventions for class names and properties. 

GetDataType is checking only for 3 types as for now since that's all I needed (number, carchar2 and date).

http://alexander-d.com/t4/
