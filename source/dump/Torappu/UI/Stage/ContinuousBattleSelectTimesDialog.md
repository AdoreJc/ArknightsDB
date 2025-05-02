# ContinuousBattleSelectTimesDialog

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIAnimationLocation _aniEnter`

- `SimpleLayoutContent _content`

- `RectTransform _backRect`

- `Boolean m_hasInited`

- `AnimationSwitchTween m_enterSwitchTween`

- `Adapter m_adapter`

- `Int32 m_stageApCost`

- `Int32 m_currentAp`

- `Int32 m_apOwnedIncludingApItem`


## Methods

- `Void _InitIfNot()`

- `ApStatus CalculateApStatus(Int32)`

- `Void OnBackClick()`

- `Void OnSelectTimes(Int32)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ContinuousBattleSelectTimesDialog : UICompDialog`1
{
	public const Int32 NOT_SELECT_COUNT; // 0x0
	private UIAnimationLocation _aniEnter; // 0x48
	private SimpleLayoutContent _content; // 0x58
	private RectTransform _backRect; // 0x60
	private Boolean m_hasInited; // 0x68
	private List`1 m_itemList; // 0x70
	private AnimationSwitchTween m_enterSwitchTween; // 0x78
	private Adapter m_adapter; // 0x80
	private Int32 m_stageApCost; // 0x88
	private Int32 m_currentAp; // 0x8c
	private Int32 m_apOwnedIncludingApItem; // 0x90
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_CalculateApStatus; // 0x18
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x20
	private static DelegateBridge __Hotfix0_OnSelectTimes; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f8c430 VA: 0x75955a4430
	protected override Void OnRender(Options options) { }
	// RVA: 0x2f8c8c0 VA: 0x75955a48c0
	protected override Void OnInit() { }
	// RVA: 0x2f8c6e0 VA: 0x75955a46e0
	private Void _InitIfNot() { }
	// RVA: 0x2f8c820 VA: 0x75955a4820
	private ApStatus CalculateApStatus(Int32 times) { }
	// RVA: 0x2f8ca5c VA: 0x75955a4a5c
	public Void OnBackClick() { }
	// RVA: 0x2f8cb48 VA: 0x75955a4b48
	public Void OnSelectTimes(Int32 times) { }
	// RVA: 0x2f8cc48 VA: 0x75955a4c48
	public Void .ctor() { }
	// RVA: 0x2f8cd2c VA: 0x75955a4d2c
	private Void <>xLuaBaseProxy_OnInit() { }
}
```