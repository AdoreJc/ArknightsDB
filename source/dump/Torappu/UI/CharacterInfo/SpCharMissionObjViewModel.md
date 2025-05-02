# SpCharMissionObjViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `String charId`

- `String missionId`

- `Int32 sortId`

- `String condSpriteId`

- `String condDesc`

- `Boolean isFullfilled`

- `Boolean isComplete`


## Methods

- `Void LoadData(SpCharMissionData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class SpCharMissionObjViewModel : IHotfixable
{
	public String charId; // 0x10
	public String missionId; // 0x18
	public Int32 sortId; // 0x20
	public String condSpriteId; // 0x28
	public String condDesc; // 0x30
	public List`1 rewards; // 0x38
	public Boolean isFullfilled; // 0x40
	public Boolean isComplete; // 0x41
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d66288 VA: 0x759537e288
	public Void LoadData(SpCharMissionData missionData) { }
	// RVA: 0x2d661c4 VA: 0x759537e1c4
	public Void .ctor() { }
}
```