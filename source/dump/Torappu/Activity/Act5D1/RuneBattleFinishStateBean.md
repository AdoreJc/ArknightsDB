# RuneBattleFinishStateBean

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `SquadItemStruct assistSquad`

- `BattleStageInfo battleStage`

- `CharUISkinStruct randomIllust`

- `Int32 leftHp`

- `Boolean isNewRecord`

- `Int32 runeValue`


## Methods

- `Void InitInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class RuneBattleFinishStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public SquadItemStruct[] squadList; // 0x18
	public SquadItemStruct assistSquad; // 0x20
	public List`1 runeList; // 0x30
	public BattleStageInfo battleStage; // 0x38
	public CharUISkinStruct randomIllust; // 0xa8
	public Int32 leftHp; // 0xb8
	public Boolean isNewRecord; // 0xbc
	public Int32 runeValue; // 0xc0
	private static DelegateBridge __Hotfix0_InitInfo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x31c6a98 VA: 0x75957dea98
	public Void InitInfo() { }
	// RVA: 0x31c9ae8 VA: 0x75957e1ae8
	public Void .ctor() { }
}
```