# FifthAnnivExploreGroupChooseView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `TwoStateToggle _groupInfoToogle`

- `Text _groupNameText`

- `UIAtlasImage _groupIconImg`

- `UIAtlasObject _groupIconAtlasObject`

- `UIAnimationLocation _infoPanelSelectAnim`

- `UIAnimationLocation _enterAnim`

- `Boolean m_isInited`

- `AnimationSwitchTween m_selectTween`

- `AnimationSwitchTween m_enterTween`


## Methods

- `Void _InitIfNot()`

- `Void _TryConsumeGuideAutoShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupChooseView : DataBinder`1, IHotfixable
{
	private TwoStateToggle _groupInfoToogle; // 0x20
	private List`1 _groupChoiceItemViews; // 0x28
	private Text _groupNameText; // 0x30
	private UIAtlasImage _groupIconImg; // 0x38
	private UIAtlasObject _groupIconAtlasObject; // 0x40
	private UIAnimationLocation _infoPanelSelectAnim; // 0x48
	private UIAnimationLocation _enterAnim; // 0x58
	private Boolean m_isInited; // 0x68
	private AnimationSwitchTween m_selectTween; // 0x70
	private AnimationSwitchTween m_enterTween; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__TryConsumeGuideAutoShow; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x291b634 VA: 0x7594f33634
	private Void _InitIfNot() { }
	// RVA: 0x291b82c VA: 0x7594f3382c
	public override Void OnValueChanged(FifthAnnivExploreGroupChooseProperty property) { }
	// RVA: 0x291ba5c VA: 0x7594f33a5c
	private Void _TryConsumeGuideAutoShow() { }
	// RVA: 0x291bae4 VA: 0x7594f33ae4
	public Void .ctor() { }
}
```