# EnemyDuelEmoticonPageComponent

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelEmoticonController _controller`

- `StateEngine _stateEngine`

- `AnimationCurve _barrageWeightCurve`

- `Int32 _barrageLaneCount`

- `Int64 _maxBarrageInterval`

- `RectTransform _barrageContainer`

- `EnemyDuelEmoticonBarrageItem _prefabBarrageItem`

- `BarrageManager m_barrageManager`

- `GameObjectPool m_barragePool`

- `Boolean <isEmoticonDisabled>k__BackingField`


## Properties

- `Boolean isEmoticonDisabled`


## Methods

- `Boolean get_isEmoticonDisabled()`

- `Void set_isEmoticonDisabled(Boolean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnBtnEmoticonClicked()`

- `Void _OnReceiveEmojiMsg(Object)`

- `Void _ShowEmoticonItem(EnemyDuelEmojiData)`

- `GameObject <OnCreate>b__17_0(GameObjectPool)`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEmoticonPageComponent : PageSingleComponent, IValueMsgReceiver
{
	public const Int32 MSG_BTN_EMOTICON_CLICKED; // 0x0
	public const Int32 MSG_HIDE_EMOTICON_PANEL; // 0x0
	private EnemyDuelEmoticonController _controller; // 0x20
	private StateEngine _stateEngine; // 0x28
	private AnimationCurve _barrageWeightCurve; // 0x30
	private Int32 _barrageLaneCount; // 0x38
	private Int64 _maxBarrageInterval; // 0x40
	private RectTransform _barrageContainer; // 0x48
	private EnemyDuelEmoticonBarrageItem _prefabBarrageItem; // 0x50
	private BarrageManager m_barrageManager; // 0x58
	private GameObjectPool m_barragePool; // 0x60
	private Boolean <isEmoticonDisabled>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_isEmoticonDisabled; // 0x0
	private static DelegateBridge __Hotfix0_set_isEmoticonDisabled; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnBtnEmoticonClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnReceiveEmojiMsg; // 0x28
	private static DelegateBridge __Hotfix0__ShowEmoticonItem; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isEmoticonDisabled { get; set; }

	// RVA: 0x297d504 VA: 0x7594f95504
	public Boolean get_isEmoticonDisabled() { }
	// RVA: 0x297e894 VA: 0x7594f96894
	public Void set_isEmoticonDisabled(Boolean value) { }
	// RVA: 0x2984d20 VA: 0x7594f9cd20
	protected override Void OnCreate() { }
	// RVA: 0x29850c8 VA: 0x7594f9d0c8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x298519c VA: 0x7594f9d19c
	private Void _OnBtnEmoticonClicked() { }
	// RVA: 0x2985314 VA: 0x7594f9d314
	private Void _OnReceiveEmojiMsg(Object arg) { }
	// RVA: 0x29853f4 VA: 0x7594f9d3f4
	private Void _ShowEmoticonItem(EnemyDuelEmojiData param) { }
	// RVA: 0x2985664 VA: 0x7594f9d664
	public Void .ctor() { }
	// RVA: 0x29856d4 VA: 0x7594f9d6d4
	private GameObject <OnCreate>b__17_0(GameObjectPool _) { }
	// RVA: 0x2985780 VA: 0x7594f9d780
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```