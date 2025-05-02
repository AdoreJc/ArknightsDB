# TuningProductOrcheItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `UIAnimationLocation _animationLocation`

- `Text _orcheItemName`

- `Text _orcheDesc`

- `LayoutElement _layoutElement`

- `String m_orcheItemId`


## Properties

- `String orcheItemId`

- `Single layoutSpacingHeight`


## Methods

- `String get_orcheItemId()`

- `Void set_layoutSpacingHeight(Single)`

- `Void Render(TuningOrcheModel)`

- `Void SampleMovingAnim(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductOrcheItemView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animationLocation; // 0x18
	private Text _orcheItemName; // 0x28
	private Text _orcheDesc; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private String m_orcheItemId; // 0x40
	private static DelegateBridge __Hotfix0_get_orcheItemId; // 0x0
	private static DelegateBridge __Hotfix0_set_layoutSpacingHeight; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SampleMovingAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String orcheItemId { get; }
	public Single layoutSpacingHeight { set; }

	// RVA: 0x2336068 VA: 0x759494e068
	public String get_orcheItemId() { }
	// RVA: 0x23360d0 VA: 0x759494e0d0
	public Void set_layoutSpacingHeight(Single value) { }
	// RVA: 0x2336164 VA: 0x759494e164
	public Void Render(TuningOrcheModel model) { }
	// RVA: 0x2336268 VA: 0x759494e268
	public Void SampleMovingAnim(Single percent) { }
	// RVA: 0x233630c VA: 0x759494e30c
	public Void .ctor() { }
}
```