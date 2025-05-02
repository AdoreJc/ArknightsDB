# BattleFinishDropPryInfoView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `CanvasGroup _frame`

- `Single _fadeinDur`

- `GameObject _normalTag`

- `GameObject _easyTag`

- `BattleFinishDropInfoView _dropInfoView`

- `LayoutGroup _layoutGroup`


## Properties

- `Boolean rendering`


## Methods

- `Void Render(DropInfoGroupViewModel)`

- `Void _RenderFrame(DropInfoGroupViewModel)`

- `Boolean get_rendering()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishDropPryInfoView : MonoBehaviour, IHotfixable
{
	private const Int32 HORIZONTAL_LAYOUT_GROUP_PADDING_LEFT_NO_TAG; // 0x0
	private const Int32 HORIZONTAL_LAYOUT_GROUP_PADDING_LEFT_WITH_TAG; // 0x0
	private CanvasGroup _frame; // 0x18
	private Single _fadeinDur; // 0x20
	private GameObject _normalTag; // 0x28
	private GameObject _easyTag; // 0x30
	private BattleFinishDropInfoView _dropInfoView; // 0x38
	private LayoutGroup _layoutGroup; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderFrame; // 0x8
	private static DelegateBridge __Hotfix0_get_rendering; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean rendering { get; }

	// RVA: 0x2e8e2d0 VA: 0x75954a62d0
	public Void Render(DropInfoGroupViewModel viewModel) { }
	// RVA: 0x2e8e390 VA: 0x75954a6390
	private Void _RenderFrame(DropInfoGroupViewModel viewModel) { }
	// RVA: 0x2e8e4e0 VA: 0x75954a64e0
	public Boolean get_rendering() { }
	// RVA: 0x2e8e550 VA: 0x75954a6550
	public Void .ctor() { }
}
```