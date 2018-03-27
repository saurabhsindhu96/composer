---
layout: default
title: ValidatedConcept (Common API)
section: api
sidebar: sidebars/accordion-toc0.md
excerpt: The Client, Admin, and Runtime components of Hyperledger Composer
index-order: 1247
---
[Overview](api-doc-index)  -  [Common API](allData#common-api)  -  [Client API](allData#client-api)  -  [Admin API](allData#admin-api)  -  [Runtime API](allData#runtime-api)
# ValidatedConcept

Resource is an instance that has a type. The type of the resource
specifies a set of properites (which themselves have types).


Type information in Composer is used to validate the structure of
Resource instances and for serialization.


Resources are used in Composer to represent Assets, Participants, Transactions and
other domain classes that can be serialized for long-term persistent storage.

### Details

- **Extends** Concept

- **Module** common



### See also
- See {@link Resource}



## Method Summary
| Name | Returns | Description |
| :---- | :-------- | :----------- |
| [addArrayValue](#addarrayvalue) | `void` | Adds an array property value, validating that it does not violate the model  |
| [setPropertyValue](#setpropertyvalue) | `void` | Sets a property, validating that it does not violate the model  |
| [validate](#validate) | `void` | Validates the instance against its model  |



## Inherited Method Summary
| Supertype | Name | Returns | Description |
| :-------- | :--- | :-------- | :----------- |
| Concept |[isConcept](#isconcept) | `boolean` | Determine if this typed is a concept  |
| Typed |[getType](#gettype) | `string` | Get the type of the instance (a short name, not including namespace)  |
| Typed |[getFullyQualifiedType](#getfullyqualifiedtype) | `string` | Get the fully-qualified type name of the instance (including namespace)  |
| Typed |[getNamespace](#getnamespace) | `string` | Get the namespace of the instance  |
| Typed |[instanceOf](#instanceof) | `boolean` | Check to see if this instance is an instance of the specified fully qualified type name  |



# Method Details


## setPropertyValue
_ setPropertyValue( string propname, string value )_


Sets a property, validating that it does not violate the model







### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**propName**| string |*Yes*|the name of the field|
|**value**| string |*Yes*|the value of the property|










## addArrayValue
_ addArrayValue( string propname, string value )_


Adds an array property value, validating that it does not violate the model







### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**propName**| string |*Yes*|the name of the field|
|**value**| string |*Yes*|the value of the property|










## validate
_ validate(  )_


Validates the instance against its model.







### See also






### Parameters

No parameters







 

##Inherited methods




## isConcept
_boolean isConcept(  )_


**Inherited from:**  Concept

Determine if this typed is a concept.





### Returns
{@link boolean} - True if this typed is a concept, false if not.




### See also






### Parameters

No parameters










## getType
_string getType(  )_


**Inherited from:**  Typed

Get the type of the instance (a short name, not including namespace).





### Returns
{@link string} - The type of this object




### See also






### Parameters

No parameters










## getFullyQualifiedType
_string getFullyQualifiedType(  )_


**Inherited from:**  Typed

Get the fully-qualified type name of the instance (including namespace).





### Returns
{@link string} - The fully-qualified type name of this object




### See also






### Parameters

No parameters










## getNamespace
_string getNamespace(  )_


**Inherited from:**  Typed

Get the namespace of the instance.





### Returns
{@link string} - The namespace of this object




### See also






### Parameters

No parameters










## instanceOf
_boolean instanceOf( String fqt )_


**Inherited from:**  Typed

Check to see if this instance is an instance of the specified fully qualified type name.





### Returns
{@link boolean} - True if this instance is an instance of the specified fully qualified type name, false otherwise.




### See also






### Parameters
| Name | Type | Mandatory | Description |
| :-----------  | :----------- | :----------- | :----------- |
|**fqt**| String |*Yes*|The fully qualified type name.|








 