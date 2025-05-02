# SandboxV2DungeonReadArchiveState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _backTransform`

- `SandboxV2DungeonReadArchiveView _view`

- `Boolean m_isInited`

- `SandboxV2DungeonReadArchiveStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _OnBgClicked()`

- `Void _OnArchiveItemClick(Int32)`

- `Void _ConfirmArchiveSelect()`

- `Void _OnReadArchiveConfirmResponse(SandboxV2ReadArchiveResponse)`

- `Void OnBackClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonReadArchiveState : PopupFadeState, IValueMsgReceiver
{
	private RectTransform _backTransform; // 0x70
	private SandboxV2DungeonReadArchiveView _view; // 0x78
	private Boolean m_isInited; // 0x80
	private SandboxV2DungeonReadArchiveStateBean m_stateBean; // 0x88
	public const Int32 MSG_BG_CLICK; // 0x0
	public const Int32 MSG_ARCHIVE_ITEM_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnBgClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnArchiveItemClick; // 0x28
	private static DelegateBridge __Hotfix0__ConfirmArchiveSelect; // 0x30
	private static DelegateBridge __Hotfix0__OnReadArchiveConfirmResponse; // 0x38
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x252afc0 VA: 0x7594b42fc0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x252b028 VA: 0x7594b43028
	protected override Void OnEnter() { }
	// RVA: 0x252b680 VA: 0x7594b43680
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x252b1cc VA: 0x7594b431cc
	private Void _InitIfNot() { }
	// RVA: 0x252b748 VA: 0x7594b43748
	private Void _OnBgClicked() { }
	// RVA: 0x252b868 VA: 0x7594b43868
	private Void _OnArchiveItemClick(Int32 day) { }
	// RVA: 0x252bc38 VA: 0x7594b43c38
	private Void _ConfirmArchiveSelect() { }
	// RVA: 0x252bfd8 VA: 0x7594b43fd8
	private Void _OnReadArchiveConfirmResponse(SandboxV2ReadArchiveResponse response) { }
	// RVA: 0x252c5d4 VA: 0x7594b445d4
	public Void OnBackClicked() { }
	// RVA: 0x252c7fc VA: 0x7594b447fc
	public Void .ctor() { }
	// RVA: 0x252c954 VA: 0x7594b44954
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```