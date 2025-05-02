# SandboxV2QuestTrackerState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _enterAnim`

- `SandboxV2QuestTrackerView _view`

- `Boolean m_isInited`

- `Tween m_enterTween`

- `SandboxV2QuestTrackerProperty m_property`


## Methods

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _UpdateData()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnItemSelect(String)`

- `Void _OpenArchive()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2QuestTrackerState : SandboxV2TrackerState, IValueMsgReceiver
{
	private UIAnimationLocation _enterAnim; // 0x80
	private SandboxV2QuestTrackerView _view; // 0x90
	private Boolean m_isInited; // 0x98
	private Tween m_enterTween; // 0xa0
	private SandboxV2QuestTrackerProperty m_property; // 0xa8
	public const Int32 ON_ITEM_SELECT; // 0x0
	public const Int32 ON_OPEN_ARCHIVE; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0__UpdateData; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnItemSelect; // 0x30
	private static DelegateBridge __Hotfix0__OpenArchive; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2553964 VA: 0x7594b6b964
	protected override Void OnEnter() { }
	// RVA: 0x2553ccc VA: 0x7594b6bccc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25539e4 VA: 0x7594b6b9e4
	private Void _InitIfNot() { }
	// RVA: 0x2553bf0 VA: 0x7594b6bbf0
	private Void _PlayEnterAnim() { }
	// RVA: 0x2553a8c VA: 0x7594b6ba8c
	private Void _UpdateData() { }
	// RVA: 0x2554544 VA: 0x7594b6c544
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2554630 VA: 0x7594b6c630
	private Void _OnItemSelect(String selectedId) { }
	// RVA: 0x2554898 VA: 0x7594b6c898
	private Void _OpenArchive() { }
	// RVA: 0x2554b98 VA: 0x7594b6cb98
	public Void .ctor() { }
	// RVA: 0x2554cac VA: 0x7594b6ccac
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```