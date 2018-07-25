# Glossary

**SpatialOS terms**<br/>
See the [SpatialOS glossary](https://docs.improbable.io/reference/latest/shared/glossary) for terms specific to SpatialOS.

**Unreal GDK repositories**<br/>
* The SpatialOS Unreal GDK: https://github.com/improbable/UnrealGDK
* Starter Project: https://github.com/improbable/UnrealGDKStarterProject
* Test Suite: https://github.com/improbable/UnrealGDKTestSuite
* Titanium Tiger: https://github.com/improbable/titanium-tiger

**Unreal GDK terms**<br/>

| Term | Description | 
| ---- | ---- |
| codegen | Legacy system for generating interop code from SpatialOS. See “interop code” listing below and the [SpatialOS documentation on codegen](https://docs.improbable.io/reference/13.1/shared/spatial-cli/spatial-worker-codegen). |
| ICG | Short for “Interop Code Generator”. See “Interop Code Generator” listing. |
| interop | Short for “interoperable” and “interoperability”. See [Stack Overflow](https://stackoverflow.com/questions/5300383/interoperability). |
| Interop Code Generator | An Unreal toolbar plugin which takes a set of Unreal classes and generates routing code (called "type bindings") that enables automated communication between Unreal and SpatialOS. See documentation on [Interop Code Generator](interop.md).|
|interop code |The contents of ` .schema` files and `SpatialTypeBinding` files which the Interop Code Generator creates. See the [SpatialOS website documentation’s .schema introduction](https://docs.improbable.io/reference/latest/shared/schema/introduction) for more information. |
| type bindings | Generated by the Interop Code Generator,  type bindings link SpatialOS entities and components to Unreal Actors and components. The type bindings are `SpatialTypeBinding` files and usually stored in `<Project Root>/workers/unreal/Game/source/<GameName>/Generated/` (where `Project Root` is the root of you project and  `GameName` is the name of your game). See documentation on [Interop Code Generator](interop.md).|

[//]: # (Editorial review status: Full review 2018-07-23)
[//]: # (Issues to deal with, but not limited to:)
[//]: # (1. Check naming of Titanium Tiger)