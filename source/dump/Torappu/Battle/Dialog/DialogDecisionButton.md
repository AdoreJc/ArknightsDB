# DialogDecisionButton

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `Text _optionText`

- `Button _optionButton`

- `Single _fadeTime`

- `Ease _easeType`

- `Int32 <optionIndex>k__BackingField`


## Properties

- `Int32 optionIndex`

- `Button optionButton`


## Methods

- `Int32 get_optionIndex()`

- `Void set_optionIndex(Int32)`

- `Button get_optionButton()`

- `Void UpdateData(BattleDialogOption)`

- `Void Hide(Boolean)`

- `Void OnDestroy()`

- `Void <Hide>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogDecisionButton : MonoBehaviour, IHotfixable
{
	private Text _optionText; // 0x18
	private Button _optionButton; // 0x20
	private Single _fadeTime; // 0x28
	private Ease _easeType; // 0x2c
	private Graphic[] _fade; // 0x30
	private Int32 <optionIndex>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_optionIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_optionIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_optionButton; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 optionIndex { get; set; }
	public Button optionButton { get; }

	// RVA: 0x1d1fe1c VA: 0x7594337e1c
	public Int32 get_optionIndex() { }
	// RVA: 0x1d1fe84 VA: 0x7594337e84
	public Void set_optionIndex(Int32 value) { }
	// RVA: 0x1d1ff00 VA: 0x7594337f00
	public Button get_optionButton() { }
	// RVA: 0x1d1ff68 VA: 0x7594337f68
	public Void UpdateData(BattleDialogOption option) { }
	// RVA: 0x1d20234 VA: 0x7594338234
	public Void Hide(Boolean fast) { }
	// RVA: 0x1d2049c VA: 0x759433849c
	private Void OnDestroy() { }
	// RVA: 0x1d20584 VA: 0x7594338584
	public Void .ctor() { }
	// RVA: 0x1d205f4 VA: 0x75943385f4
	private Void <Hide>b__12_0() { }
}
```