# SideStoryTrailViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RetroTrailRewardItem data`

- `Boolean isAvail`

- `Boolean isAlreadyGet`

- `Boolean isAchieve`

- `UniCollectionInfo uniCollectionInfo`


## Methods

- `Void InitData(Int32, RetroTrailRewardItem, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SideStoryTrailViewModel : IHotfixable
{
	public RetroTrailRewardItem data; // 0x10
	public Boolean isAvail; // 0x18
	public Boolean isAlreadyGet; // 0x19
	public Boolean isAchieve; // 0x1a
	public UniCollectionInfo uniCollectionInfo; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2f17574 VA: 0x759552f574
	public Void InitData(Int32 totalCount, RetroTrailRewardItem i_data, Boolean i_isAlreadyGet) { }
	// RVA: 0x2f1767c VA: 0x759552f67c
	public Void .ctor() { }
}
```