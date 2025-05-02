# OpenServerV2ChainLoginItemData

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `ChainLoginData chainLoginData`

- `OpenServerCheckinItemState state`


## Methods

- `Boolean IsEmpty()`

- `Int32 GetColorId()`

- `OpenServerItemData GetOpenServerItemData()`

- `OpenServerCheckinItemState GetCheckinState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2ChainLoginItemData : ICheckinItemData, IHotfixable
{
	public ChainLoginData chainLoginData; // 0x10
	public OpenServerCheckinItemState state; // 0x18
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_GetColorId; // 0x8
	private static DelegateBridge __Hotfix0_GetOpenServerItemData; // 0x10
	private static DelegateBridge __Hotfix0_GetCheckinState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2859284 VA: 0x7594e71284
	public Boolean IsEmpty() { }
	// RVA: 0x2859304 VA: 0x7594e71304
	public Int32 GetColorId() { }
	// RVA: 0x285937c VA: 0x7594e7137c
	public OpenServerItemData GetOpenServerItemData() { }
	// RVA: 0x28593f4 VA: 0x7594e713f4
	public OpenServerCheckinItemState GetCheckinState() { }
	// RVA: 0x285945c VA: 0x7594e7145c
	public Void .ctor() { }
}
```