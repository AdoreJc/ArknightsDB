# ActMultiV3ManualTitleSelectView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `TwoStateToggle _commitToggle`

- `ActMultiV3TitlePagerView _prefixPagerView`

- `ActMultiV3TitlePagerView _suffixPagerView`

- `UIAnimationLocation _scrollAnimLocation`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `AnimationSwitchTween m_switchTween`

- `Int32 m_cachedInitSeqNum`


## Methods

- `Void OnConfirmTitle()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualTitleSelectView : DataBinder`1, IHotfixable
{
	private TwoStateToggle _commitToggle; // 0x20
	private ActMultiV3TitlePagerView _prefixPagerView; // 0x28
	private ActMultiV3TitlePagerView _suffixPagerView; // 0x30
	private UIAnimationLocation _scrollAnimLocation; // 0x38
	private Boolean m_inited; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private AnimationSwitchTween m_switchTween; // 0x60
	private Int32 m_cachedInitSeqNum; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirmTitle; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x311d48c VA: 0x759573548c
	public override Void OnValueChanged(ActMultiV3TitleSelectProperty property) { }
	// RVA: 0x311d7d4 VA: 0x75957357d4
	public Void OnConfirmTitle() { }
	// RVA: 0x311d5b4 VA: 0x75957355b4
	private Void _InitIfNot() { }
	// RVA: 0x311d878 VA: 0x7595735878
	public Void .ctor() { }
}
```