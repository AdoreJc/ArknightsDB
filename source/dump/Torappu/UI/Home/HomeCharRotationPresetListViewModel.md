# HomeCharRotationPresetListViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `String currPresetInstId`

- `Int32 maxPresetNum`

- `Int32 createPresetSeqNum`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetListViewModel : IHotfixable
{
	public ListDict`2 presetItemList; // 0x10
	public String currPresetInstId; // 0x18
	public Int32 maxPresetNum; // 0x20
	public Int32 createPresetSeqNum; // 0x24
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x27dd2bc VA: 0x7594df52bc
	public Void LoadData() { }
	// RVA: 0x27e1168 VA: 0x7594df9168
	public Void .ctor() { }
}
```