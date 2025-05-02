# Act24sideBattleFinishMeldingDropInfoView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `CanvasGroup _frame`

- `Single _fadeinDur`

- `Act24sideBattleFinishMeldingDropInfoItemView _dropInfoView`


## Properties

- `Boolean rendering`


## Methods

- `Boolean get_rendering()`

- `Void Render(Act24sideBattleFinishMeldingDropViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleFinishMeldingDropInfoView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _frame; // 0x18
	private Single _fadeinDur; // 0x20
	private Act24sideBattleFinishMeldingDropInfoItemView _dropInfoView; // 0x28
	private static DelegateBridge __Hotfix0_get_rendering; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean rendering { get; }

	// RVA: 0x32917c0 VA: 0x75958a97c0
	public Boolean get_rendering() { }
	// RVA: 0x3291830 VA: 0x75958a9830
	public Void Render(Act24sideBattleFinishMeldingDropViewModel viewModel) { }
	// RVA: 0x32918e0 VA: 0x75958a98e0
	public Void .ctor() { }
}
```