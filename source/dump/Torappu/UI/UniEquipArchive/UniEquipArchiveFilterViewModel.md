# UniEquipArchiveFilterViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Boolean showTrack`

- `UniEquipArchiveFilterEquipState equipUnlockState`

- `Int32 fastSeq`

- `Int32 trackNum`


## Methods

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveFilterViewModel : IHotfixable
{
	public Boolean showTrack; // 0x10
	public UniEquipArchiveFilterEquipState equipUnlockState; // 0x14
	public Int32 fastSeq; // 0x18
	public Int32 trackNum; // 0x1c
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x22e476c VA: 0x75948fc76c
	public Void InitData() { }
	// RVA: 0x22e565c VA: 0x75948fd65c
	public Void .ctor() { }
}
```