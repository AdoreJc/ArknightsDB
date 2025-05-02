# ActMultiV3BattleFinishDefenceResultView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `Text _textBossDamage`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishDefenceResultView : ActMultiV3BattleFinishResultViewBase
{
	private Text _textBossDamage; // 0x38
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x317d48c VA: 0x759579548c
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x317d4f4 VA: 0x75957954f4
	protected override Void OnRender() { }
	// RVA: 0x317d6c0 VA: 0x75957956c0
	public Void .ctor() { }
}
```