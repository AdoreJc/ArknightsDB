# HandBookStageViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandbookStoryStageData data`

- `Boolean isUnlock`

- `GetInfo addon`

- `String skinId`


## Methods

- `Void InitData(HandbookStoryStageData, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookStageViewModel : IHotfixable
{
	public HandbookStoryStageData data; // 0x10
	public List`1 unlockInfo; // 0x18
	public Boolean isUnlock; // 0x20
	public GetInfo addon; // 0x28
	public String skinId; // 0x30
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ebc7d8 VA: 0x75954d47d8
	public Void InitData(HandbookStoryStageData inputData, Int32 chrinstID) { }
	// RVA: 0x2ebc768 VA: 0x75954d4768
	public Void .ctor() { }
}
```