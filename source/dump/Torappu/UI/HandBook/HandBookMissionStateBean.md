# HandBookMissionStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Boolean isInited`


## Methods

- `Void ApplyMissionData()`

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookMissionStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public List`1 missionList; // 0x18
	public Dictionary`2 cardList; // 0x20
	public Dictionary`2 friendshipTeamData; // 0x28
	public Boolean isInited; // 0x30
	private static DelegateBridge __Hotfix0_ApplyMissionData; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e9e61c VA: 0x75954b661c
	public Void ApplyMissionData() { }
	// RVA: 0x2e9dfa8 VA: 0x75954b5fa8
	public Void InitData() { }
	// RVA: 0x2e9ede4 VA: 0x75954b6de4
	public Void .ctor() { }
}
```