# Act20sideCartDetailState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCarObject _carObject`

- `Transform _container`

- `Act20sideCarDetailCompObj _trunk01`

- `Act20sideCarDetailCompObj _trunk02`

- `Act20sideCarDetailCompObj _os01`

- `Act20sideCarDetailCompObj _os02`

- `Act20sideCarDetailCompObj _headStock`

- `Act20sideCarDetailCompObj _roof`

- `Single _cartScaler`

- `Transform _avatarContainer`

- `GameObject _panelLevel`

- `Text _levelText`

- `UIAtlasImage _npcIcon`

- `Text _name`

- `Text _nickNumber`

- `Single _avatarViewScale`

- `Act20sideCarObject m_carObject`

- `PlayerAvatarView m_avatarView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _RenderComp(Param, CartAccessoryPos, Act20sideCarDetailCompObj, Dictionary`2)`

- `Void _ApplyCharInfo(Param)`

- `Void _ApplyAvatar(AvatarInfo)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartDetailState : State
{
	private Act20sideCarObject _carObject; // 0x50
	private Transform _container; // 0x58
	private Act20sideCarDetailCompObj _trunk01; // 0x60
	private Act20sideCarDetailCompObj _trunk02; // 0x68
	private Act20sideCarDetailCompObj _os01; // 0x70
	private Act20sideCarDetailCompObj _os02; // 0x78
	private Act20sideCarDetailCompObj _headStock; // 0x80
	private Act20sideCarDetailCompObj _roof; // 0x88
	private Single _cartScaler; // 0x90
	private Transform _avatarContainer; // 0x98
	private GameObject _panelLevel; // 0xa0
	private Text _levelText; // 0xa8
	private UIAtlasImage _npcIcon; // 0xb0
	private Text _name; // 0xb8
	private Text _nickNumber; // 0xc0
	private Single _avatarViewScale; // 0xc8
	private Act20sideCarObject m_carObject; // 0xd0
	private PlayerAvatarView m_avatarView; // 0xd8
	private Boolean m_isInited; // 0xe0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderComp; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__ApplyCharInfo; // 0x20
	private static DelegateBridge __Hotfix0__ApplyAvatar; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32f0e38 VA: 0x7595908e38
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f0e9c VA: 0x7595908e9c
	private Void _InitIfNot() { }
	// RVA: 0x32f0fc0 VA: 0x7595908fc0
	private Void _RenderComp(Param param, CartAccessoryPos pos, Act20sideCarDetailCompObj compObj, Dictionary`2 accessories) { }
	// RVA: 0x32f111c VA: 0x759590911c
	protected override Void OnEnter() { }
	// RVA: 0x32f12d0 VA: 0x75959092d0
	private Void _ApplyCharInfo(Param param) { }
	// RVA: 0x32f14b0 VA: 0x75959094b0
	private Void _ApplyAvatar(AvatarInfo avatarInfo) { }
	// RVA: 0x32f1664 VA: 0x7595909664
	public Void .ctor() { }
	// RVA: 0x32f16e8 VA: 0x75959096e8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```