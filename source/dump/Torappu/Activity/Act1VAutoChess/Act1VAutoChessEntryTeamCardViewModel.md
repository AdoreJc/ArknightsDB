# Act1VAutoChessEntryTeamCardViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Boolean isEnemyTeam`

- `String cardTeamId`

- `String teamLogoId`

- `String charIconId`

- `Boolean isSelected`

- `Boolean isLocked`


## Methods

- `Void LoadData(String, String)`

- `Void SetSelected(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryTeamCardViewModel : Act1VAutoChessEntryBaseSubViewModel, IHotfixable
{
	public Boolean isEnemyTeam; // 0x24
	public String cardTeamId; // 0x28
	public String teamLogoId; // 0x30
	public String charIconId; // 0x38
	public Boolean isSelected; // 0x40
	public Boolean isLocked; // 0x41
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetSelected; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x33575d0 VA: 0x759596f5d0
	public Void LoadData(String teamId, String actId) { }
	// RVA: 0x33577e0 VA: 0x759596f7e0
	public Void SetSelected(Boolean selected) { }
	// RVA: 0x3357860 VA: 0x759596f860
	public Void .ctor() { }
}
```