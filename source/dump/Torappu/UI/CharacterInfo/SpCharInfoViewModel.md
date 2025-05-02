# SpCharInfoViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `String charId`

- `Boolean hasSpCharInDB`

- `String spCharNames`

- `String missionUnlockSpCharName`

- `Boolean isMissionUnlocked`

- `Boolean hasMissionFullfilled`

- `Boolean isAllMissionComplete`


## Properties

- `Boolean hasMissionInProgress`


## Methods

- `Boolean get_hasMissionInProgress()`

- `Void LoadData(PlayerCharacter)`

- `Void _LoadSpCharInfo(PlayerCharacter)`

- `Void _LoadMissionInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class SpCharInfoViewModel : IHotfixable
{
	public String charId; // 0x10
	public Boolean hasSpCharInDB; // 0x18
	public String spCharNames; // 0x20
	public String missionUnlockSpCharName; // 0x28
	public Boolean isMissionUnlocked; // 0x30
	public Boolean hasMissionFullfilled; // 0x31
	public Boolean isAllMissionComplete; // 0x32
	private static DelegateBridge __Hotfix0_get_hasMissionInProgress; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadSpCharInfo; // 0x10
	private static DelegateBridge __Hotfix0__LoadMissionInfo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hasMissionInProgress { get; }

	// RVA: 0x2d65080 VA: 0x759537d080
	public Boolean get_hasMissionInProgress() { }
	// RVA: 0x2d65100 VA: 0x759537d100
	public Void LoadData(PlayerCharacter playerChar) { }
	// RVA: 0x2d651c4 VA: 0x759537d1c4
	private Void _LoadSpCharInfo(PlayerCharacter playerChar) { }
	// RVA: 0x2d65478 VA: 0x759537d478
	private Void _LoadMissionInfo() { }
	// RVA: 0x2d65714 VA: 0x759537d714
	public Void .ctor() { }
}
```