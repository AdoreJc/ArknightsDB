# BossRushStageChooseViewModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String detailStageGroupId`

- `Int32 completeStageCount`

- `Int32 normalStageCount`

- `Boolean showEnterAnim`


## Methods

- `Void LoadData(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageChooseViewModel : IHotfixable
{
	public ListDict`2 stageList; // 0x10
	public String detailStageGroupId; // 0x18
	public Int32 completeStageCount; // 0x20
	public Int32 normalStageCount; // 0x24
	public Boolean showEnterAnim; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2e70a5c VA: 0x7595488a5c
	public Void LoadData(String actId, Boolean showEnterAnim) { }
	// RVA: 0x2e71180 VA: 0x7595489180
	public Void .ctor() { }
}
```