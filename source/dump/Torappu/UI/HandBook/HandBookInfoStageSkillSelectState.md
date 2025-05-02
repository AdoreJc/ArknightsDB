# HandBookInfoStageSkillSelectState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookInfoStageSkillSelectView _view`

- `RectTransform _backRt`

- `Boolean m_inited`


## Methods

- `Void StartBattle()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SelectSkill(Int32)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStageSkillSelectState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 ON_SKILL_SELECT; // 0x0
	private HandBookInfoStageSkillSelectView _view; // 0x70
	private RectTransform _backRt; // 0x78
	private Boolean m_inited; // 0x80
	private static DelegateBridge __Hotfix0_StartBattle; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__SelectSkill; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ea0e2c VA: 0x75954b8e2c
	public Void StartBattle() { }
	// RVA: 0x2ea0fb8 VA: 0x75954b8fb8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ea101c VA: 0x75954b901c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2ea1208 VA: 0x75954b9208
	protected override Void OnEnter() { }
	// RVA: 0x2ea10c8 VA: 0x75954b90c8
	private Void _SelectSkill(Int32 idx) { }
	// RVA: 0x2ea127c VA: 0x75954b927c
	private Void _InitIfNot() { }
	// RVA: 0x2ea1430 VA: 0x75954b9430
	public Void .ctor() { }
	// RVA: 0x2ea14a0 VA: 0x75954b94a0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```