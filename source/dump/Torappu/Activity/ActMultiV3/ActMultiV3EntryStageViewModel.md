# ActMultiV3EntryStageViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Boolean hasNewUnlockedStage`


## Methods

- `Void LoadData(String, PlayerMultiV3Activity, ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryStageViewModel : IHotfixable
{
	public Boolean hasNewUnlockedStage; // 0x10
	public Dictionary`2 stages; // 0x18
	public Dictionary`2 modeStarCount; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30f1638 VA: 0x7595709638
	public Void LoadData(String actId, PlayerMultiV3Activity playerActivity, ActMultiV3Data actData) { }
	// RVA: 0x30f1b08 VA: 0x7595709b08
	public Void .ctor() { }
}
```