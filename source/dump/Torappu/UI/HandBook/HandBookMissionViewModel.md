# HandBookMissionViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String powerId`

- `Int32 teamFavorTotal`

- `Int32 teamSort`

- `Single teamPer`

- `HandbookTeamMission teamMissionData`

- `Int32 isAvailable`


## Methods

- `Int32 CompareTo(HandBookMissionViewModel)`

- `Void LoadData(HandbookTeamMission, HandBookTeamViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookMissionViewModel : IComparable`1
{
	public String powerId; // 0x10
	public Int32 teamFavorTotal; // 0x18
	public Int32 teamSort; // 0x1c
	public Single teamPer; // 0x20
	public List`1 viewModelList; // 0x28
	public HandbookTeamMission teamMissionData; // 0x30
	public Int32 isAvailable; // 0x38


	// RVA: 0x2e9ef48 VA: 0x75954b6f48
	public Int32 CompareTo(HandBookMissionViewModel anotherTeam) { }
	// RVA: 0x2e9ecc8 VA: 0x75954b6cc8
	public Void LoadData(HandbookTeamMission teamMission, HandBookTeamViewModel teamViewModel) { }
	// RVA: 0x2e9ec40 VA: 0x75954b6c40
	public Void .ctor() { }
}
```