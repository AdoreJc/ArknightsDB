# MedalBarListItem

**Namespace:** `Torappu.UI.Medal`


## Fields

- `TwoStateToggle _twoStateToggle`

- `Text _medalName`

- `Text _medalName2`

- `Text _countText`

- `RectTransform _rect`

- `GameObject _showCountBan`

- `AnimationWrapper _animationWrapper`

- `UIStringEvent onClickEvent`

- `LayoutElement _layoutSize`

- `Boolean showCountFlag`

- `Tween m_currentTween`

- `MedalTypeViewModel m_cacheViewModel`

- `RenderCache m_renderCache`


## Methods

- `Void Render(MedalTypeViewModel)`

- `Void OnClick()`

- `Void SetCount(Int32, Single, Single)`

- `Void ResetProgressAnim()`

- `Void SwitchProgressDisplay(Boolean)`

- `Void StopProgressAnim()`

- `Single <SetCount>b__17_0()`

- `Void <SetCount>b__17_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalBarListItem : MonoBehaviour, IHotfixable
{
	private static String LIST_ITEM_ANIM; // 0x0
	private TwoStateToggle _twoStateToggle; // 0x18
	private Text _medalName; // 0x20
	private Text _medalName2; // 0x28
	private Text _countText; // 0x30
	private RectTransform _rect; // 0x38
	private GameObject _showCountBan; // 0x40
	private AnimationWrapper _animationWrapper; // 0x48
	public UIStringEvent onClickEvent; // 0x50
	private LayoutElement _layoutSize; // 0x58
	public Boolean showCountFlag; // 0x60
	private Tween m_currentTween; // 0x68
	private MedalTypeViewModel m_cacheViewModel; // 0x70
	private RenderCache m_renderCache; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_SetCount; // 0x18
	private static DelegateBridge __Hotfix0_ResetProgressAnim; // 0x20
	private static DelegateBridge __Hotfix0_SwitchProgressDisplay; // 0x28
	private static DelegateBridge __Hotfix0_StopProgressAnim; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x27a79dc VA: 0x7594dbf9dc
	public Void Render(MedalTypeViewModel viewModel) { }
	// RVA: 0x27a7d78 VA: 0x7594dbfd78
	public Void OnClick() { }
	// RVA: 0x27a7e40 VA: 0x7594dbfe40
	public Void SetCount(Int32 delta, Single minHeight, Single maxHeight) { }
	// RVA: 0x27a8270 VA: 0x7594dc0270
	public Void ResetProgressAnim() { }
	// RVA: 0x27a8314 VA: 0x7594dc0314
	public Void SwitchProgressDisplay(Boolean showDetails) { }
	// RVA: 0x27a8468 VA: 0x7594dc0468
	public Void StopProgressAnim() { }
	// RVA: 0x27a8510 VA: 0x7594dc0510
	public Void .ctor() { }
	// RVA: 0x27a85c8 VA: 0x7594dc05c8
	private static Void .cctor() { }
	// RVA: 0x27a8634 VA: 0x7594dc0634
	private Single <SetCount>b__17_0() { }
	// RVA: 0x27a8658 VA: 0x7594dc0658
	private Void <SetCount>b__17_1(Single x) { }
}
```