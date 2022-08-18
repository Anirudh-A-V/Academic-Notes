# Entity

The basic concept that the ER model represents is an **entity**, which is a thing or object in the real world with an independent existence.

An entity may be an **object with a physical existence** (for example, a particular person, car, house, or employee) or it may be an **object with a conceptual existence** (for instance, a company, a job, or a university course).

Each entity has [[Attributes]]—the particular properties that describe it.

---
## Entity Type
An **entity type** defines a collection (or set) of entities that have the same attributes.

The collection of all entities of a particular entity type in the database at any point in time is called an **entity set** or entity collection.

An entity type describes the **schema or intension** for a set of entities that share the same structure.

The collection of entities of a particular entity type is grouped into an entity set, which is also called the **extension of the entity type**.

![[employee-company.jpg]]

---
## Key Attributes of an Entity Type

An important constraint on the entities of an entity type is the **key or uniqueness constraint** on attributes.

An entity type usually has one or more attributes whose values are distinct for each individual entity in the entity set.
Such an attribute is called a key attribute, and its values can be used to identify each entity uniquely.

Sometimes several attributes together form a key, meaning that the combination of the attribute values must be distinct for each entity.

If a set of attributes possesses this property, the proper way to represent this in the ER model that we describe here is to define a composite attribute and designate it as a key attribute of the entity type.

Notice that such a composite key must be minimal; that is, all component attributes must be included in the composite attribute to have the uniqueness property.

Superfluous attributes must not be included in a key. Some entity types have more than one key attribute.

**Weak entity type** - An entity type having no key

---
## Weak Entity Type

Entity types that do not have key attributes of their own are called **weak entity types**. In contrast, regular entity types that do have a key attribute are called **strong entity types**.

Entities belonging to a weak entity type are identified by being related to specific entities from another entity type in combination with one of their attribute values.

We call this other entity type the **identifying or owner entity type**, and we call the relationship type that relates a weak entity type to its owner the **identifying relationship** of the weak entity type.

A weak entity type **always has a total participation constraint** (existence dependency) with respect to its identifying relationship because a weak entity cannot be identified without an owner entity.

### Weak Entity Type – partial key
A weak entity type normally has a **partial key**, which is the attribute that can uniquely identify weak entities that are related to same owner entity.

In our example, if we assume that no two dependents of the same employee ever have the same first name, the attribute Name of **DEPENDENT** is the partial key.

In the worst case, a composite attribute of all the weak entity’s attributes will be the partial key.

