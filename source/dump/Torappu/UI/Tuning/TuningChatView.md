# TuningChatView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `SimpleLayoutContent _content`

- `TuningProductBagPanelView _bagPanelPrefab`

- `Transform _bagPanelContainer`

- `UIAnimationLocation _chatAnim`

- `Boolean m_isInited`

- `TuningChatViewModel m_cachedViewModel`

- `TuningProductBagPanelView m_bagView`

- `UIStateFinder m_stateFinder`

- `Adapter m_adapter`

- `AnimationSwitchTween m_chatAnimTween`


## Methods

- `Void _InitIfNot()`

- `Void _OnBagTypeSelect(String)`

- `Void _OnBagProductSelect(String)`

- `Void _OnOpenTuning()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatView : DataBinder`1
{
	private SimpleLayoutContent _content; // 0x20
	private TuningProductBagPanelView _bagPanelPrefab; // 0x28
	private Transform _bagPanelContainer; // 0x30
	private UIAnimationLocation _chatAnim; // 0x38
	private Boolean m_isInited; // 0x48
	private TuningChatViewModel m_cachedViewModel; // 0x50
	private TuningProductBagPanelView m_bagView; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private Adapter m_adapter; // 0x70
	private AnimationSwitchTween m_chatAnimTween; // 0x78
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnBagTypeSelect; // 0x10
	private static DelegateBridge __Hotfix0__OnBagProductSelect; // 0x18
	private static DelegateBridge __Hotfix0__OnOpenTuning; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x231ff24 VA: 0x7594937f24
	public override Void OnValueChanged(TuningChatProperty property) { }
	// RVA: 0x2320064 VA: 0x7594938064
	private Void _InitIfNot() { }
	// RVA: 0x23203e4 VA: 0x75949383e4
	private Void _OnBagTypeSelect(String typeId) { }
	// RVA: 0x2320500 VA: 0x7594938500
	private Void _OnBagProductSelect(String productId) { }
	// RVA: 0x232061c VA: 0x759493861c
	private Void _OnOpenTuning() { }
	// RVA: 0x23206d0 VA: 0x75949386d0
	public Void .ctor() { }
}
```