# SimpleCrossAppShareRemakeModel

**Namespace:** `Torappu.UI.CrossAppShare`


## Fields

- `CrossAppShareLayoutContentModel layoutContentModel`


## Methods

- `SimpleCrossAppShareRemakeModel GetSimpleModel()`

- `Void CollectModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrossAppShare
public class SimpleCrossAppShareRemakeModel : ISimpleCrossAppShareRemakeModelCollector, ICrossAppShareModelCollector, IHotfixable, ILuaCallCSharp
{
	public CrossAppShareLayoutContentModel layoutContentModel; // 0x10
	public Dictionary`2 compModelDict; // 0x18
	private static DelegateBridge __Hotfix0_GetSimpleModel; // 0x0
	private static DelegateBridge __Hotfix0_CollectModel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2bc33e0 VA: 0x75951db3e0
	public SimpleCrossAppShareRemakeModel GetSimpleModel() { }
	// RVA: 0x2bc3448 VA: 0x75951db448
	public Void CollectModel() { }
	// RVA: 0x2bc34ac VA: 0x75951db4ac
	public Void .ctor() { }
}
```