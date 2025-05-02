# UIStageInfo

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _stageNoLabel`

- `Text _stageNameLabel`

- `Text _stageOperationLabel`


## Methods

- `Void SetData(BattleStageInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIStageInfo : MonoBehaviour, IHotfixable
{
	private const String OPERATION_TEXT; // 0x0
	private Text _stageNoLabel; // 0x18
	private Text _stageNameLabel; // 0x20
	private Text _stageOperationLabel; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2040e40 VA: 0x7594658e40
	public Void SetData(BattleStageInfo stageInfo) { }
	// RVA: 0x20415f0 VA: 0x75946595f0
	public Void .ctor() { }
}
```