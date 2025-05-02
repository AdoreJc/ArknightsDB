# FifthAnnivExploreCheckPointResultViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreTargetData targetData`

- `String stageDisplayNum`

- `String blockedStageCode`

- `Boolean isExpand`

- `Boolean isWin`

- `Boolean isFailed`

- `Boolean isBlockedByLevel`

- `String groupCode`

- `String groupName`

- `String groupIconId`

- `String unexpandTitle`

- `String unexpandDesc`

- `String expandSubtitle`

- `String expandTitle`

- `String expandDesc`

- `String clinkHint`


## Methods

- `Void LoadData()`

- `Void OnExpand()`

- `Void _LoadFailStageData(String)`

- `Void _LoadPassTargetData(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreCheckPointResultViewModel
{
	public FifthAnnivExploreTargetData targetData; // 0x10
	public String stageDisplayNum; // 0x18
	public String blockedStageCode; // 0x20
	public Boolean isExpand; // 0x28
	public Boolean isWin; // 0x29
	public Boolean isFailed; // 0x2a
	public Boolean isBlockedByLevel; // 0x2b
	public String groupCode; // 0x30
	public String groupName; // 0x38
	public String groupIconId; // 0x40
	public String unexpandTitle; // 0x48
	public String unexpandDesc; // 0x50
	public String expandSubtitle; // 0x58
	public String expandTitle; // 0x60
	public String expandDesc; // 0x68
	public String clinkHint; // 0x70


	// RVA: 0x290b04c VA: 0x7594f2304c
	public Void LoadData() { }
	// RVA: 0x290ba08 VA: 0x7594f23a08
	public Void OnExpand() { }
	// RVA: 0x290c4f0 VA: 0x7594f244f0
	private Void _LoadFailStageData(String stageId) { }
	// RVA: 0x290c170 VA: 0x7594f24170
	private Void _LoadPassTargetData(String targetId, Boolean isWin) { }
	// RVA: 0x290bcc0 VA: 0x7594f23cc0
	public Void .ctor() { }
}
```