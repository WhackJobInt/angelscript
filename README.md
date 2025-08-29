# AngelScript Lib (Catharsis Reborn/Ultrapatch+Angel)

The lib used for Catharsis Reborn and Ultrapatch+Angel

## Note

This lib has been modified to work with Visual Studio 2010's compiler, some native AS features might have been disabled or modified

### Modifications

- Unique Id Setter with `RegisterObjectType` (default is -1), can be used on asITypeInfo or asIScriptObject
- Owner setter/getter - meant for objects like NPCs and Players (`GetOwner` and `HasOwner`)
- "Script class" getter/setter - Objects are tied to a single class